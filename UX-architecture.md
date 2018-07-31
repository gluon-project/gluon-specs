# UX Architecture

## Rooms

* Matrix user box
  * Avatar
  * Name / address
* Room 0 (Invite pending)
* Room 1
* Room 2
* Room 3
  * Message list
  * Message input field
  * "+"
    * Send tokens
    * Request tokens
    * Send Claim (Contact tab)
    * Send Photo
    * Send video
    * Send location
  * Members (Nav bar button)
    * Member list
    * Invite member
* New Room
  * Create new room 
    * Room name
  * Join existing room
    * Search room name


## Wallet
* Wallet user box
  * Avatar
  * Name / address
* Ether 
  * Balance
  * Self funding info box (link to shapeshift.io)
  * Transaction History
* Token 1
* Token 2
* Token 3
  * Balance
  * Buy
    * Graph
    * Reserve pool
    * Total supply
    * Price
    * Amount
    * Gas price
      * Slow
      * Medium
      * Fast
  * Sell
    * Graph
    * Reserve pool
    * Total supply
    * Reward
    * Amount
    * Gas price
      * Slow
      * Medium
      * Fast
  * Transaction History
    * Transaction 1
    * Transaction 2
    * Transaction 3
      * Date
      * Sender
      * Receiver
      * Amount 
      * Tx progress
      * "+"
        * Repeat transaction
        * Share
          * Share in room
            * Room list
            * New Room
              * Create new room 
                * Room name
              * Add existing
                * Email, name or matrix ID
          * Share in fb, twitter, etc.
          * Share url
        * Open in Etherscan
* New Token (form)
  * Create new token
    * Name
    * Symbol
    * Avatar ? (@oed)
    * Type
      * Fixed 
        * Total amount
        * Decimals
      * Bonding curve
        * Graph
        * Exponent

  * Add existing
    * Token list
    * Address
    * Name
    * Symbol


## Send-request

* Wallet user box
  * Avatar
  * Name / address
* Send
  * Select token
    * Token list
    * New Token (form)
  * Set Amount
    * Amount key pad
  * Select receiver
    * Local contact list
    * Room contact list
    * Add new contact (form)
  * Share in room
    * Room list
    * New Room (form)
* Request
  * Select token
    * Token list
    * New Token (form)
  * Set Amount
    * Amount keypad
  * Share in Room
    * Room list
    * New Room (form)


## Contacts

* Locally saved contacts
  * Contact 1 (0x10)
  * Contact 2 (0x11)
  * Contact 3 (0x12)
    * Name: John
      * Claim Signed by 0x01
      * Claim Signed by 0x02
      * Claim Signed by 0x03
    * Name: Jonny
      * Claim Signed by 0x01
      * Claim Signed by 0x05
    * Phone nr: 4239589324
      * Claim Signed by 0x01
      * Claim Signed by 0x02
    * Skill: Designer
      * Claim Signed by 0x08
      * Claim Signed by 0x09
    * Award: Best in show
      * Claim Signed by 0x08
    * Create New claim
      * Save
      * Sign with uPort and save
    * Delete (all claims for this DID)
    * Actions
      * Send tokens
      * Send matrix message (Create room)
      * Share contact (select claims)
        * Share in Room
          * Room list
          * New Room (form)
        * Share in fb, twitter, etc.
        * Share url 
* Contacts loaded from matrix rooms (claims)
  * Contact 1
  * Contact 2
  * Contact 3
    * Claims list
    * Create New claim
      * Save
      * Sign with uPort and save
    * Actions
      * Send tokens
      * Send matrix message (Create room)
      * Share contact (select claims)
        * Share in Room
          * Room list
          * New Room (form)
        * Share in fb, twitter, etc.
        * Share url 
* Create new contact
  * Name
  * Address
  * Save
  * Sign with uPort and save

## Settings
* Clear local cache

## About
* Idea and project
* Functionality
* Some usage ideas
* Technical stuff

# Landing page

`https://tx.gluon.space/matrix_event_id`

## Transaction
* Date
* Sender
* Receiver
* Amount 
* Tx progress

## About gluon
* Feature list
* Etc.
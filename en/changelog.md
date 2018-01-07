---
title: Changelog
layout: default
---

# Delta Chat Changelog

## v0.12.0
2018-01-07

* Gossip keys of other group members in the encrypted payload (will also be evaluated in one of the next versions)
* Use SHA-256 instead of SHA-1 in signatures
* Make the permanent notification clickable
* Update permanent notification after import
* Fix rendering of system messages
* Various bug fixes
* Update Albanian, French, Italian, Norwegian, Polish, Russian and Turkish translations

## v0.11.4
2017-12-17

* Add option to initiate Autocrypt Key Transfer
* Connect after importing a backup
* Reading memory hole headers
* Add Albanian translation
* Update German, Italian, Polish, Portuguese, Russian, Turkish and Ukrainian translations

## v0.10.0
2017-11-29

* Fix usage of multiple private keys
* Fix various memory leaks
* Update English, Portuguese and Turkish translations

## v0.9.9
2017-11-18

* Alternate include order for F-Droid
* Add Serbian translation
* Update Catalan, Dutch, English, French, German, Hungarian, Italian, Polish, Portuguese, Russian, Spanish, Tamil, Telugu and Ukrainian translations

## v0.9.8
2017-11-15

* Fix a bug that avoids chat creation under some circumstances (bug introduced in 0.9.7)

## v0.9.7
2017-11-14

* Archive chats or delete chats by a long press
* Notify the user in the chatlist about contact requests of known users or of other Delta Chat clients
* Show messages only for explicitly wanted chats
* Show more detailed reasons about failed end-to-end-encryptions
* Explicit option to leave a group
* Do not show the padlock if end-to-end-encryption is disabled by the user
* Also import images from a backup when using a different device with different paths
* Add copy-to-clipboard function for "About / Info"
* Rework Emoji-code
* Add Norwegian Bokmål translation
* Add Tamil translation
* Add Turkish translation
* Update Catalan, German, French, Italian, Korean, Dutch, Polish, Portuguese, Russian, Telugu and Ukrainian translations

## v0.9.6
2017-10-18

* Support keys generated with multiple subkeys eg. from K-9
* Show PDFs and other attachments with bad names
* Bug fixes

## v0.9.5
2017-10-08

* Backup export and import function
* Query password before export
* Move replies from normal E-Mail-Clients to the "Chats" folder
* Improve helping MUAs on showing chat threads
* Improve onboarding
* Add URL to default footer
* Test a different approach for battery saving in this release
* Update French, Italian, German, Polish, Portuguese, Russian and Ukrainian translations

## v0.9.4
2017-08-23

* Introduce an editable "Status" field that is shown eg. in email footers
* Editable and synchronized group images
* Show the subject of messages that cannot be decrypted
* Do not send "Read receipts" when decryption fails
* Do not request "Read receipts" from normal MUAs as there are too many MUAs responding with weird, non-standard formats
* Deleting a chat always deletes all messages from the device permanently
* Ignore messages from mailing lists
* Do not spread the original authors name nor address on forwarding
* Encrypt mails send to SMTP and to IMAP the same way
* Improve showing HTML-mails
* Cleanup Android code
* Remove badge counter on app restart
* Add Ukrainian translation
* Add Telugu translation
* Add Catalan translation
* Update German, Spanish, French, Hungarian, Italian, Polish, Portuguese and Russian translations

## v0.9.3
2017-07-13

* Introduce "Read receipts" and avoid social pressure to leave it activated
* Improve encryption dialog in profile
* Fix marking messages as "seen" when opening the contact requests
* Ignore signature.asc files of signed-only messages
* Update Polish, Portuguese and Russian translations

## v0.9.2
2017-06-28

* Encrypt group chats
* Cryptographically sign messages
* Validate signatures of incoming messages ("Info" shows the state)
* Show a little lock beside end-to-end-encrypted messages with a validated signature
* If end-to-end-encryption is available on sending time, guarantee the message not to be sent without end-to-end-encryption later
* Show special characters in HTML-mails
* Help MUAs on showing chat threads
* Show attachments from multipart/alternative structures
* Upgrade from Autocrypt Level 0 to Level 1; as the levels are not compatible, encryption on mixed setups does not happen
* Update Polish, Portuguese, Spanish and French translations

## v0.9.1
2017-06-04

* Profile: Improve encryption state dialog
* Improved video quality of short clips
* Make encryption-dialog localizable
* Update Russian translation

## v0.9.0
2017-06-01

* Add end-to-end-encrypting following the OpenPGP and Autocrypt standards
* Add a function to compare keys
* Profile: Add option to copy the email address to the clipboard
* Pimp GUI

## v0.1.36
2017-05-04

* Support camera on Android Nougat

## v0.1.34
2017-05-03

* Link to new homepage https://delta.chat
* Localizable Help-URLs

## v0.1.33
2017-04-29

* Better support for right-to-left (RTL) languages, taking advantage of
  Android 4.2 (Jelly Bean MR1, API level 17).
* Send PNG files without resizing and converting to JPEG
* If JPEG files are send without compression, they still appear as image, not as attached files
* Raise-to-speak defaults to false
* Unify long click behaviour
* Support Android's system function "Delete data"
* Replies to messages pop up automatically even if send from other email addresses (typical scenario for alias addresses)
* Fix group-replies from normal email-clients. 

## v0.1.32
2017-04-22

* Update Spanish and Portuguese translations
* Update internal sqlite library to version 3.18.0, released on 2017-03-28
* Remove more of the custom language handling, use Android's routines instead
* General code cleanup
* Play GIF files
* Option to disable autoplaying GIF files
* When sending contacts, only use the names the receivers have set themselves
* Show some hints when long-pressing icons in the action bar

## v0.1.29
2017-04-19

* Add Russian translation
* For outgoing (group-)messages, only use the names the receivers have set themselves

## v0.1.28
2017-04-14

* Pimp notifications
* Bug fixes

## v0.1.27
2017-04-12

* Use a permanent foreground service for reliable notifications
* Monitor the IMAP-IDLE thread and reconnect if IMAP-IDLE seems to hang
* Various battery and background optimizations

## v0.1.25
2017-04-04

* Use system or user selected video player.
* Do not connect if not configured (avoids a warning on the first time startup)
* Add  vertical scrollbar, eg. to settings activities.
* Pimp GUI and logo.
* Update Korean.

## v0.1.24
2017-03-31

* Share images and documents from other apps to Delta Chat
* Offer to mailto:-link-support to other apps
* Ignore implausible sending time of incoming messages; use the receive time in these rare cases
* Show errors only when Delta Chat is in foreground
* Dynamically adapt video bitrate for longer videos to an attachment-size of max. 25 MB

## v0.1.23
2017-03-28

* Retry connecting to IMAP if there is not network available on the first try
* Notify about new messages if the app is not active for hours, optimize battery consumption

## v0.1.22
2017-03-22

* Show HTML-only messages
* Show connection errors
* Add options for SSL/TLS and STARTTLS
* Automatic account configuration, if possible
* Recode large videos
* Add Hungarian translation
* Add Korean translation

## v0.1.21
2017-03-10

* Record and send voice messages
* Record and send videos
* Send and play music
* Send contacts and email addresses
* Sending and opening attachments of any type
* Share and open commands for all attachments
* Accept VCards send to us by other apps
* Clickable email addresses
* Update Polish translation
* Fix tablet startup bug
* Close the app when using the lock-app-via-pincode function
* Protect data by using a content provider for sharing
* Try to clear the task switcher's screenshots when locking the app via pincode
* Pimp GUI

## v0.1.20
2017-02-16

* Avoid unwanted downloads of lots of old messages
* Make the "Chats" folder visible if the server hides new folders by default
* Fix a crash when the server returns empty folders
* Update Polish and Portuguese translations
* Use API level 25 (Nougat 7.1) as target

## v0.1.18
2017-02-11

* Add Polish translation
* Use a new default background for chats
* Improve typography by using the system font instead of a custom resource font
* Remove custom plural handling, use Android's routines instead
* Remove unused source code and strings
* More fixes of lint errors and warnings

## v0.1.17
2017-02-07

* Drop two unnecessary permissions: ACCESS_COARSE_LOCATION and ACCESS_FINE_LOCATION
* Really add French translation
* Update Portuguese translation
* Start fixing translation handling of the program
* Remove special "foss" build, because the whole program is free now.

## v0.1.16
2017-02-06

* Add French translation
* Fix some lint errors and warnings

## v0.1.15
2017-01-31

* Prepare for release on [F-Droid](https://f-droid.org/)

# telegram-bot-organizer
telegram bot to manage reminders to yourself 

### TMP
- full server
- indicate necessary api:
    - create/read/update/delete files in conversation
    - create/read/update/delete messages in conversation
    - ?change properties of conversation
- compose a set of instructions to the bot
    - add note
        - set date
        - notification pattern (once, repeated(repetition pattern))
    - change note
    - delete note
    - suspend a note
- structure the set on instructions
- compose a server side logic of note managment, storage, notification

#### into action!  
- server
    - state of manager (list, to notify , etc)
        - storage
        - on...
    - merge changes from client into state of the manager
# Payload ORI recieves from social25

## Organic Customers

### The payload for when the customer clicks directly on the button that will say “Get Started”

```json
{
    "id": "f782c5bd-3e8e-4845-8493-cc3c689523ef",
    "ext_identifier": null,
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T14:14:44",
    "modified_timestamp": "2022-08-01T14:14:46.311046",
    "type": "EVENT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Commencez",
    "auxiliary_data": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTg0OTgzNDg2NjYzMDU1NzU5ODU4MjIyMjg4MDc2OAZDZD",
        "title": "Commencez",
        "payload": "{\"type\":\"default\",\"payload\":{\"query\":\"Hi\"}}"
    },
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T142005Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=36410cd31cd9559196de01715678116cfbca49e184e02635b35b0d25cdf5b0ae"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

### The payload for when the customer decides to type “Get Started” instead of clicking on the button

```json
{
    "id": "0ff49621-dfaa-4257-a11d-efb012bd3548",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTg1MjE5OTg0NDQ3NzkyODg0NzY4NjA5NTYwMTY2NAZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T14:16:52",
    "modified_timestamp": "2022-08-01T14:16:54.502411",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Get started",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T142032Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=53423532158880fac6fcf162500032a5dbc537b10f52a879829aa4ff8db2023c"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

## Customers comign through an Ad

### The payload for when the customer clicks on the button that is shown on the ad page (that button will also say “Get Started”)

```json
{
    "id": "63f9e71f-a257-4c8a-b289-988f10ff71ba",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MDMyODE0NzEwMjA1MzMzODA5MTI4OTA1MTEzNgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:02:54",
    "modified_timestamp": "2022-08-01T14:03:03.516002",
    "type": "IG_SHARE",
    "status": "RECEIVED",
    "outbound": false,
    "text": "[Shared an Instagram Post]",
    "auxiliary_data": {
        "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17934574169316054&signature=AbyCiCtzJ3maAXc6XR4idmNSqdvxMXWTO2uuUSCHo_xa-Cdzu6ck3qLQbDz1AhdfUe7pIrkv9XUUZ9iGQv5kCS7fucxPq95vByVQkhzphlwFI2RyUce_2dHsqfmKphoMOYhWxxpSb8G2Xhtm52A6TJvJLq3Sa_SiVNdJ7xJIb5Wo_bWvxf5mxeq0xAJ1ehprIomYrOYOXMT7zQZB_lBWgn6JxHw9s1Q"
    },
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T140717Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=6db9eeba54fd7c9b59b371434415cb929d2944a43335c8f00921605711db935e"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```
```json
{
    "id": "f6e336b2-493f-4e43-8524-e9f194088714",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MDMzNzM4MzQ5NzQ5MTUwODkwNjA0MDQ5MjAzMgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:02:54",
    "modified_timestamp": "2022-08-01T13:02:58.611191",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Bonjour",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-prod.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIGN4KF4P5O5Q5CDA%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T132853Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=03d823e035f7bb16130dfadd6a2b09c1d66512e5e87c318779d53bff41fc11a8"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

### The payload for when the customer decides to type “Get Started” on the ad page instead of clicking the button

```json
{
    "id": "73da1e84-fc52-44fe-b238-b798464f4d18",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MjY1NzU0MTI3MjM0MDEyMTgzODY0MjI2NjExMgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:05:00",
    "modified_timestamp": "2022-08-01T14:03:12.867574",
    "type": "IG_SHARE",
    "status": "RECEIVED",
    "outbound": false,
    "text": "[Shared an Instagram Post]",
    "auxiliary_data": {
        "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17934574169316054&signature=AbyLcCg5BpmXkKzCbUgH4Ake_t_RDoJ5ZbtcVw1kkPw4SuIdzjjM8vIfi1FIg-ECgfPr8qlMpD2VQfMD--Gqgj94BKOfaSBgHk0tJXeBVPCBHkn5iw9Rb3oEUjteOTOeBrCk48tbzwvqOG2qsApmsILrM8Ybh4FutD-T9oHnVL5DQntV4-ntIwsotjnzyX5RNTy75SndTxzgulMi5ASIEV5bw5DLzHA"
    },
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T140749Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=551193569540b87c1b5d72111ee0146d1d285ff978c4a390560dd72b40513821"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```
```json
{
    "id": "c8445cfa-971b-4440-9ebf-c22862b4b554",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MjY2NDY1NTE2Njk1ODQyNzU1ODY3NTIxODQzMgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:05:01",
    "modified_timestamp": "2022-08-01T13:05:03.892280",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Get started",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-prod.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIGN4KF4P5O5Q5CDA%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T133022Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=879a49ab01b34d86f5b0cde390d9d72fd8865a85d97a6e28e98681321fdb5b0e"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

##  A customer coming through an ad on a story reply

### The payload for when the customer clicks on the button that is shown on the ad page (that button will also say “Get Started”)

```json
{
    "id": "04258884-0c93-44ed-8b1c-62e87b9e7991",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NDM0NTg2NDAwOTk3NDYyMjU2MDU2Mzc1NzA1NgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:06:32",
    "modified_timestamp": "2022-08-01T13:50:11.333155",
    "type": "STORY_REPLY",
    "status": "RECEIVED",
    "outbound": false,
    "text": "[Empty story reply]",
    "auxiliary_data": {
        "reply_to": {
            "story": {
                "id": "17958541324774936",
                "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17958541324774936&signature=Abz3um6DHuxGx1cTJjq6yGYUjY0ZREGzf9NGfBSAKz7XXedqMYOHT6Uf8dqAM2E5XFvVLFgHT8IrApQsTNqn91N_t0vWs_Z9Q6fRHkJVrfDyrYRYewro6jTbL0uZyTGsgeuILTLJeuKetPn7zB0fcRNYZrD9fmklT7DvKfHd71-WJNtC29v4WLoPxI4PV1AOWYPQfNfJ16Dvj5VZcQINM6f_5mixivA"
            }
        }
    },
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T140817Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=f079416f1dbe7ac1bbfc8e7d88d0d62df86ff184763416f8721fe337330a8a94"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

```json
{
    "id": "5e6105d9-d38b-4812-8366-65bdd1b774a3",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NDM1MTY5NTY3MTQxMjM2NDcyOTY2Mzg4MTIxNgZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:06:32",
    "modified_timestamp": "2022-08-01T13:06:35.289923",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Bonjour",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-prod.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIGN4KF4P5O5Q5CDA%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T133114Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=2431b1271918f9435631155ca2fd4906a1ad1dfc5003be640200fa582356c38e"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

### The payload for when the customer decides to type “Get Started” on the ad page instead of clicking the button

```json
{
    "id": "ff4ed285-a4a1-426d-8e79-0dd2d8fb4fd1",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NTcyODQ2NDY3MDY2NDYzMDE1MTQ4NTA2MzE2OAZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:07:47",
    "modified_timestamp": "2022-08-01T13:07:49.511541",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Get started",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-dev.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIPGXO3VGDF7JW2QQ%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T140856Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=ebadb972d52d50498d594ef3748a22a21e3a84cf09f6720a425e2ea8ef38d9bf"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```

```json
{
    "id": "ff4ed285-a4a1-426d-8e79-0dd2d8fb4fd1",
    "ext_identifier": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NTcyODQ2NDY3MDY2NDYzMDE1MTQ4NTA2MzE2OAZDZD",
    "agent_id": null,
    "agent": null,
    "tenant_id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
    "conversation_id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
    "timestamp": "2022-08-01T13:07:47",
    "modified_timestamp": "2022-08-01T13:07:49.511541",
    "type": "TEXT",
    "status": "RECEIVED",
    "outbound": false,
    "text": "Get started",
    "auxiliary_data": null,
    "custom_data": null,
    "file": null,
    "file_type": null,
    "media_title": null,
    "mime_type": null,
    "transcribe_enabled": false,
    "transcribe_in_progress": false,
    "quote": null,
    "template": null,
    "chat_user": {
        "id": "921d17f7-efa3-5cf8-82e8-89dac56b3ce0",
        "username": "Mike Hanssen",
        "first_name": null,
        "last_name": null,
        "phone_number": null,
        "gender": null,
        "profile_picture": {
            "url": "https://s3.eu-central-1.amazonaws.com/social25-prod/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "etag": "92ebaa0fbcc3449db859d5db014c456d",
            "path": "f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg",
            "type": "private",
            "title": "4801928913257705.jpg",
            "mime_type": "image/jpeg",
            "resource_type": "image",
            "secure_url": "https://social25-prod.s3.amazonaws.com/f4ae7a6002cf419ba304f8ae2e46a712/Instagram/profile_images/4801928913257705.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIGN4KF4P5O5Q5CDA%2F20220801%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Date=20220801T133159Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=25edc2a64329ab83f87341c9058c1eb1914d685521daa926cabb24efab9de9a2"
        }
    },
    "platform": "instagram",
    "platform_id": "369",
    "tenant": {
        "id": "f4ae7a60-02cf-419b-a304-f8ae2e46a712",
        "name": "EF Education First Ltd.",
        "org_id": "00D0Y000000bOqsUAE"
    },
    "conversation_state": "AUTO_BOT"
}
```
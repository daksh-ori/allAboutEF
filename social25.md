# Facebook and Instagram payload as per Social25

## payload social25 receives from instagram

## Organic Customers

### **Payload for when the customer clicks directly on the button that will say “Get Started”**

```json
{
    "object": "instagram",
    "entry": [
        {
            "time": 1659363285336,
            "id": "17841401332206571",
            "messaging": [
                {
                    "sender": {
                        "id": "4801928913257705"
                    },
                    "recipient": {
                        "id": "17841401332206571"
                    },
                    "timestamp": 1659363284520,
                    "postback": {
                        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTg0OTgzNDg2NjYzMDU1NzU5ODU4MjIyMjg4MDc2OAZDZD",
                        "title": "Commencez",
                        "payload": "{\\"type\\":\\"default\\",\\"payload\\":{\\"query\\":\\"Hi\\"}}"
                    }
                }
            ]
        }
    ]
}
```

### **Payload for when the customer decides to type “Get Started” instead of clicking in the button**
```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659363412726,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTg1MjE5OTg0NDQ3NzkyODg0NzY4NjA5NTYwMTY2NAZDZD",
        "text": "Get started"
    },
    "standby": false
}
```

## Customers coming through an Ad

### **Payload for when the customer clicks on the button that is shown in the ad page (that button will also say “Get Started”)**
```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659358974452,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MDMyODE0NzEwMjA1MzMzODA5MTI4OTA1MTEzNgZDZD",
        "attachments": {
            "type": "share",
            "payload": {
                "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17934574169316054&signature=AbyCiCtzJ3maAXc6XR4idmNSqdvxMXWTO2uuUSCHo_xa-Cdzu6ck3qLQbDz1AhdfUe7pIrkv9XUUZ9iGQv5kCS7fucxPq95vByVQkhzphlwFI2RyUce_2dHsqfmKphoMOYhWxxpSb8G2Xhtm52A6TJvJLq3Sa_SiVNdJ7xJIb5Wo_bWvxf5mxeq0xAJ1ehprIomYrOYOXMT7zQZB_lBWgn6JxHw9s1Q"
            }
        }
    },
    "standby": false
}
```

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659358974953,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MDMzNzM4MzQ5NzQ5MTUwODkwNjA0MDQ5MjAzMgZDZD",
        "text": "Bonjour"
    },
    "standby": false
}
```

### **Payload for when the customer decides to type “Get Started” in the ad page instead of clicking the button**
```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359100729,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MjY1NzU0MTI3MjM0MDEyMTgzODY0MjI2NjExMgZDZD",
        "attachments": {
            "type": "share",
            "payload": {
                "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17934574169316054&signature=AbyLcCg5BpmXkKzCbUgH4Ake_t_RDoJ5ZbtcVw1kkPw4SuIdzjjM8vIfi1FIg-ECgfPr8qlMpD2VQfMD--Gqgj94BKOfaSBgHk0tJXeBVPCBHkn5iw9Rb3oEUjteOTOeBrCk48tbzwvqOG2qsApmsILrM8Ybh4FutD-T9oHnVL5DQntV4-ntIwsotjnzyX5RNTy75SndTxzgulMi5ASIEV5bw5DLzHA"
            }
        }
    },
    "standby": false
}
```

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359101115,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3MjY2NDY1NTE2Njk1ODQyNzU1ODY3NTIxODQzMgZDZD",
        "text": "Get started"
    },
    "standby": false
}
```

## A customer coming through an ad on a story reply

### **The payload for when the customer clicks on the button that is shown in the ad page (that button will also say “Get Started”)**

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359192253,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NDM0NTg2NDAwOTk3NDYyMjU2MDU2Mzc1NzA1NgZDZD",
        "reply_to": {
            "story": {
                "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17958541324774936&signature=Abz3um6DHuxGx1cTJjq6yGYUjY0ZREGzf9NGfBSAKz7XXedqMYOHT6Uf8dqAM2E5XFvVLFgHT8IrApQsTNqn91N_t0vWs_Z9Q6fRHkJVrfDyrYRYewro6jTbL0uZyTGsgeuILTLJeuKetPn7zB0fcRNYZrD9fmklT7DvKfHd71-WJNtC29v4WLoPxI4PV1AOWYPQfNfJ16Dvj5VZcQINM6f_5mixivA",
                "id": "17958541324774936"
            }
        }
    },
    "standby": false
}
```

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359192569,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NDM1MTY5NTY3MTQxMjM2NDcyOTY2Mzg4MTIxNgZDZD",
        "text": "Bonjour"
    }
}
```

## The payload for when the customer decides to type “Get Started” on the ad page instead of clicking the button

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359266861,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NTcyMjEyOTI2NTUzOTcyMzEyMTk0OTQwOTI4MAZDZD",
        "reply_to": {
            "story": {
                "url": "https://lookaside.fbsbx.com/ig_messaging_cdn/?asset_id=17958541324774936&signature=AbzkSMJodoMn3FGJ2GufwnIWtFqW5zaaa53KHxIXQnRlgx4iJw9tPKSgRIdAtwbDpgiJgcKO7KNzPj-w5aqN7aM6A8BqzJSJ-1I26fROXn1toW2n6lMWIibRoYqTCVbtxdYnW7OvzPTyl_RZMFkXI8GBnIafuD7IOVNIFYJFyvs8TrdMU-QrFkzvu8srAnpvqgg5YBU0DnNmvu_CJOn9URcMOUyc2Vo",
                "id": "17958541324774936"
            }
        }
    },
    "standby": false
}
```

```json
{
    "sender": {
        "id": "4801928913257705"
    },
    "recipient": {
        "id": "17841401332206571"
    },
    "timestamp": 1659359267204,
    "message": {
        "mid": "aWdfZAG1faXRlbToxOklHTWVzc2FnZAUlEOjE3ODQxNDAxMzMyMjA2NTcxOjM0MDI4MjM2Njg0MTcxMDMwMDk0OTEyODIyODQwMDUyNzc4Nzg1MTozMDYwOTc3NTcyODQ2NDY3MDY2NDYzMDE1MTQ4NTA2MzE2OAZDZD",
        "text": "Get started"
    },
    "standby": false
}
```


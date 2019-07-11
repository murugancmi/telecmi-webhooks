# telecmi-webhooks

## Incoming Missed


```
{ 
  cmiuid: '127c1480-ce5d-480a-a593',
  status: 'missed',
  from: 1401003355,
  time: 1553763981000,
  waitedsec: 143,
  direction:'inbound',
  voicemail:true,
  voicename:'15537387809818359948791.mp3'
  team: 'DID' 
}
```
## Incoming Answered

```
{ 
    cmiuid: 'a59180ef-7a17-4d6f-9f62-b3d407',
    user: '101_111xxxx',
    status: 'answered',
    to: 989xxxxx,
    from: 989xxxxx,
    direction:'inbound',
    time: 1553758498059,
    answeredsec: 7,
    team: 'Enquiry_111xxxx',
    record: true,
    filename: '1553738780981835994879.mp3' 
}
   
```

## Outgoing Missed


```
{ 
  cmiuid: '127c1480-ce5d-480a-a593',
  status: 'missed',
  from: 982xxxxxxx,
  time: 1553763981000,
  waitedsec: 143,
  direction:'outbound',
  to:942xxxxxxx,
  user:'101_1111113'
}
```
## Outgoing Answered

```
{ 
    cmiuid: 'a59180ef-7a17-4d6f-9f62-b3d407',
    status: 'answered',
    from: 989xxxxx,
    time: 1553758498059,
    answeredsec: 7,
    direction:'outbound',
    to:942xxxxxxx,
    user:'101_1111113'
    record: true,
    filename: '1553738780981835994879.mp3' 
}
   
```

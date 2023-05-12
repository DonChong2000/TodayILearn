ref: https://www.youtube.com/watch?v=Bf7vDBBOBUA&ab_channel=CodeAesthetic

# Write code thats self-explanatory

- By creating constant representing variable
Oringal:
```python
# A status of 5 singnals message sent
if status == 5
	message.markSent()
```
Modifided
```python
MESSAGE_SENT = 5
if status == MESSAGE_SENT
	message.markSent()
```

- Put saperate if condition into human language
Orignial:
```python
if(message.user.id == current_user.id and 
   (message.delivered_time() is None or (datetime.now - message.delivered_time().seconds < 300) 
   )
  )
```
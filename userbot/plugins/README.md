## Mandatory Imports
```python3
None
```
There is None Mandatory Imports. Because Var, bot and command are already automatically imported.

## Explanation
The Mandatory Imports are now automatically imported.

### Formation
Now I will show a short script to show the formation of the desired script.
```python3
@command(pattern="^.hidup", outgoing=True)
async def hello_world(event):
    if event.fwd_from:
        return
    await event.edit("**HALO DUNIA**\n\nBerikut ini mengendalikan saya juga!\n" + Var.SUDO_USERS)
```



## Useful Functions

```powershell
# Convert a file to Base64
[convert]::ToBase64String((Get-Content -path "your_file_path" -Encoding byte))
```

> The above comes in handy for file extraction because you can just copy the Base64 String to another box and decode then pipe to a file

```powershell
# Encode String as Base64
[Convert]::ToBase64String([Text.Encoding]::UTF8.GetBytes('Motörhead'))

# Decode from Base64 String
[Text.Encoding]::Utf8.GetString([Convert]::FromBase64String('TW90w7ZyaGVhZA=='))
```
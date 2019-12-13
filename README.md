# bwx-mocks

## horse

GET `/horse/`

```json

{
    "Meets": {
        "Location": "Gold Coast",
        "Races": {
            "Name": "Magic Millions",
            "Number": 1,
            "Jump": "12:10"
        }
    }
}

```

GET `horse?meetdate=2001-1-1`

```json
{
    "Meets": {
        "Location": "Gold Coast",
        "Races": {
            "Name": "Magic Millions",
            "Number": 1,
            "Jump": "12:10"
        }
    }
}
```

GET `meet?eventid=1`

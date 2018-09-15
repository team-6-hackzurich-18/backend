# backend

## POST `/test`

```json
{
    "ingredients": [
			{
                "Product": "Beef",
				"kg":0.5
			},
			{
				"Product": "Lamb",
				"kg":0.2
			}
		]
}
```

## Output
```json
{
	"ingredients": [
		{
			"Product": "Beef",
			"kg": 0.5,
			"CO2": 13.88
		},
		{
			"Product": "Lamb",
			"kg": 0.2,
			"CO2": 5.088000000000001
		}
	],
	"cost_total": 18.968000000000004
}
```
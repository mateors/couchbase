# couchbase
`Couchbase` is  distributed NoSQL cloud database.

<hr>

## create Scope

```sql
CREATE SCOPE royaltypool.raihan;
```

## create collection

```sql
CREATE COLLECTION royaltypool.raihan.client;
```

## Primary index

```sql
CREATE PRIMARY INDEX `default` ON`royaltypool`.`raihan`.`client`
```

## Insert data

```sql
INSERT INTO royaltypool.raihan.client (KEY, VALUE) VALUES('airline_4485',
	{ "callsign": "MY-AIR",
	  "country": "United States",
	  "iata": "Z1",
	  "icao": "AQZ",
	  "name": "80-My Air",
	  "id": "4444",
	   "type": "airline"} )
```

## Read data

```sql
SELECT * FROM royaltypool.raihan.client WHERE id='4444'
```

## Update data

```sql
UPDATE royaltypool.raihan.client SET country = "Bangladesh" WHERE id = "4444"
```

## Delete data
```sql
DELETE FROM royaltypool.raihan.client WHERE id='4444'
```
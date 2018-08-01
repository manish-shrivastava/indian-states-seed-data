# indian-country's states / provice seed-data for ruby on rails.

This is a seed data for indian states / province list. It is directly importable by running rake db:seed command.

## Country Table

```sql
country = Country.create( name: 'India' )
```

## States / Province Table

```sql

Province.create (country_id: country.id, name: 'andhra pradesh')
Province.create (country_id: country.id, name: 'assam')
Province.create (country_id: country.id, name: 'arunachal pradesh')
Province.create (country_id: country.id, name: 'gujrat')
Province.create (country_id: country.id, name: 'bihar')
Province.create (country_id: country.id, name: 'haryana')
Province.create (country_id: country.id, name: 'himachal pradesh')
Province.create (country_id: country.id, name: 'jammu & kashmir')
Province.create (country_id: country.id, name: 'karnataka')
Province.create (country_id: country.id, name: 'kerala')
Province.create (country_id: country.id, name: 'madhya pradesh')
Province.create (country_id: country.id, name: 'maharashtra')
Province.create (country_id: country.id, name: 'manipur')
Province.create (country_id: country.id, name: 'meghalaya')
Province.create (country_id: country.id, name: 'mizoram')
Province.create (country_id: country.id, name: 'nagaland')
Province.create (country_id: country.id, name: 'orissa')
Province.create (country_id: country.id, name: 'punjab')
Province.create (country_id: country.id, name: 'rajasthan')
Province.create (country_id: country.id, name: 'sikkim')
Province.create (country_id: country.id, name: 'tamil Nadu')
Province.create (country_id: country.id, name: 'tripura')
Province.create (country_id: country.id, name: 'uttar pradesh')
Province.create (country_id: country.id, name: 'west bengal')
Province.create (country_id: country.id, name: 'goa')
Province.create (country_id: country.id, name: 'pondichery')
Province.create (country_id: country.id, name: 'lakshdweep')
Province.create (country_id: country.id, name: 'daman & diu')
Province.create (country_id: country.id, name: 'dadra & nagar')
Province.create (country_id: country.id, name: 'chandigarh')
Province.create (country_id: country.id, name: 'andaman & nicobar')
Province.create (country_id: country.id, name: 'uttaranchal')
Province.create (country_id: country.id, name: 'jharkhand')
Province.create (country_id: country.id, name: 'chattisgarh')
Province.create (country_id: country.id, name: 'assam')

```






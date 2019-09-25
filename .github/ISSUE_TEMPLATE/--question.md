---
name: "/sale/product-proposals error result"
about: 
Hello, I am using api:
Https://api.allegro.pl/sale/product-proposals
please help me check where my problem,thank you!
I upload the product and show this result:


{
     "errors": [
         {
             "code": "ConstraintViolationException.RequireEnabledCategory",
             "message": "An error has occurred",
             "details": "Cannot create products in category: 257929",
             "path": "category.id",
             "userMessage": "It is not possible to add products to the category."
         }
     ]
}



this is my upload json:
{
	"name": "Buty sportowe wyglądają jak Nike Air Huarache czarny R.39",
	"category": {
		"id": "257929"
	},
	"eans": [],
	"images": [{
		"url": "https://a.allegroimg.com/original/11a07d/0976f4544b41a947db7ea84a1b27"
	}, {
		"url": "https://a.allegroimg.com/original/115f77/1c6984df4cba931b525867950454"
	}, {
		"url": "https://a.allegroimg.com/original/11e0bd/14a0d4a3439886cb8b0017e2eb7c"
	}, {
		"url": "https://a.allegroimg.com/original/1187cc/fe7723404ea4ac998f1d7933095f"
	}, {
		"url": "https://a.allegroimg.com/original/11f79f/7747f70a467ab58830698d897959"
	}, {
		"url": "https://a.allegroimg.com/original/11d914/6757197a4194ad23593069367417"
	}, {
		"url": "https://a.allegroimg.com/original/11fcae/0f50af974466be7a0b8497a016c0"
	}, {
		"url": "https://a.allegroimg.com/original/11070d/5a6009ab49b9ac19197901379a08"
	}, {
		"url": "https://a.allegroimg.com/original/1169c3/0035cbce44c8a510184ec43a2204"
	}, {
		"url": "https://a.allegroimg.com/original/113a8b/b219ae044673a03e13cfc36b448e"
	}],
	"parameters": [{
		"id": "15851",
		"valuesIds": ["15851_2"]
	}, {
		"id": "127048",
		"valuesIds": ["127048_64"]
	}, {
		"id": "451",
		"valuesIds": ["451_2"]
	}, {
		"id": "232289",
		"valuesIds": ["232289_366637"]
	}, {
		"id": "7108",
		"valuesIds": ["7108_52"]
	}, {
		"id": "219629",
		"valuesIds": ["219629_286869"]
	}, {
		"id": "127848",
		"valuesIds": ["127848_1"]
	}, {
		"id": "3766",
		"valuesIds": ["3766_1"]
	}, {
		"id": "64",
		"valuesIds": ["64_6"]
	}, {
		"id": "22728",
		"valuesIds": ["22728_3"]
	}, {
		"id": "203085",
		"valuesIds": ["203085_4"]
	}, {
		"id": "234173",
		"valuesIds": ["234173_8"]
	}, {
		"id": "215918",
		"values": ["number1"]
	}, {
		"id": "224017",
		"values": ["number1"]
	}],
	"description": {
		"sections": [{
			"items": [{
			    "type":"IMAGE",
				"url": "https://a.allegroimg.com/original/115f77/1c6984df4cba931b525867950454"
			}]
		}]
	}
}


---

<!-- Zanim zadasz pytanie zapoznaj się z naszymi materiałami:

[REST API](https://developer.allegro.pl/)
[Uwierzytelnianie i autoryzacja](https://developer.allegro.pl/auth/)
[Jak wystawić ofertę](https://developer.allegro.pl/sale/)
[Jak zarządzać ofertami](https://developer.allegro.pl/my_offers/)
[Jak obsługiwać zamówienia](https://developer.allegro.pl/orders/)
[Jak zarządzać zestawami i rabatami](https://developer.allegro.pl/offer_bundles/)
[Jak utworzyć ofertę wielowariantową](https://developer.allegro.pl/multi_variant_offers/)
[WebAPI](https://allegro.pl/webapi)
-->

# Lets get started
All our applications are whitelabel, so we can load any restaurant with its own details on the same application.
All images and colours are customized.

| header color  | buttons colour | header image |
| ------------- | ------------- | -------------- |
| venue.webSettings.navBackgroundColour  | venue.webSettings.primaryColour  | venue.webSettings.bannerImage |
| ![Header Background Color Example](https://github.com/qsengineers/frontend-challenge/assets/134649881/d079a57e-4c4a-4c55-bc0e-64fb3a1a41b2)  | ![Buttons Color Example](https://github.com/qsengineers/frontend-challenge/assets/134649881/159b689c-3020-45d2-92b6-57641011a5ae)  | ![Header Image Example](https://github.com/qsengineers/frontend-challenge/assets/134649881/c62f27d1-2bd7-4f35-817f-672477bc5b3a) |


- You should use this figma as reference: [figma](https://www.figma.com/file/9eUcy4OeOdqP9Ux5TyCGga/Front-end-test?type=design&node-id=7-2406)
- You can see this animation as reference to understand how screens communicate each other: [animation](https://www.figma.com/proto/9eUcy4OeOdqP9Ux5TyCGga/Front-end-test?page-id=9%3A2408&type=design&node-id=9-2409&viewport=331%2C510%2C0.19&scaling=scale-down&starting-point-node-id=9%3A2409)

This is the API endpoint you should use to fetch Restaurant details: https://run.mocky.io/v3/0453ad6e-f530-4864-b101-a7fba4980012
```

   {
    "id":7602,
    "name":"BURGERS RESTAURANT",
    "internalName":"BURGERS RESTAURANT",
    "description":null,
    "liveFlag":1,
    "demoFlag":1,
    "address1":"Rua XX-X, 1-11",
    "address2":"XXX",
    "address3":null,
    "city":"Bauru",
    "county":"BR",
    "postcode":"17012-360",
    "country":"BR",
    "timezoneOffset":"-03:00",
    "locale":"pt-BR",
    "timeZone":"America/Sao_Paulo",
    "webSettings":{
       "id":5854,
       "venueId":7602,
       "bannerImage":"https://preodemo.gumlet.io/usr/venue/7602/web/646fbf3abf9d0.png",
       "backgroundColour":"#ffffff",
       "primaryColour":"#4f372f",
       "primaryColourHover":"#4f372f",
       "navBackgroundColour":"#4f372f"
    },
    "ccy":"BRL",
    "ccySymbol":"R$",
    "currency":"R$"
 }
```

This is the API endpoint you should use to fetch Menu details: https://run.mocky.io/v3/a27e98a8-fe59-4623-be70-b9ac4a3254a7
```

  {
     "id":14730,
     "name":"FE TEST",
     "type":"MENU",
     "collapse":0,
     "sections":[
        {
           "id":242403,
           "name":"Burgers",
           "description":null,
           "position":0,
           "visible":1,
           "images":[
              {
                 "id":1550,
                 "image":"https://preodemo.gumlet.io/usr/venue/7602/section/646fbe4c64a6f.png"
              }
           ],
           "items":[
              {
                 "id":1625701,
                 "name":"Hard Core",
                 "description":"180g angus beef burger, with shredded ribs, gruyere cheese, caramelized onions, lettuce, confit tomato, special house bread, served with fried cassava and passion fruit chipotle.",
                 "alcoholic":0,
                 "price":33.00,
                 "position":0,
                 "visible":1,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1625701",
                 "images":[
                    {
                       "id":108305,
                       "image":"https://preodemo.gumlet.io/usr/venue/7602/menuItem/646fbdc8cecca.png"
                    }
                 ],
                 "available":true
              },
              {
                 "id":1625702,
                 "name":"Smash Brooks",
                 "description":"100g pressed hamburger, mozzarella cheese, pickles, red onion, grilled bacon and traditional Heinz mayonnaise.",
                 "alcoholic":0,
                 "price":0.00,
                 "position":1000,
                 "visible":1,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1625702",
                 "modifiers":[
                    {
                       "id":1101202,
                       "name":"Choose a size",
                       "minChoices":1,
                       "maxChoices":1,
                       "items":[
                          {
                             "id":7476054,
                             "name":"1 meat",
                             "price":33.00,
                             "maxChoices":1,
                             "position":0,
                             "visible":1,
                             "availabilityType":"AVAILABLE_NOW",
                             "available":true
                          },
                          {
                             "id":7476055,
                             "name":"2 meats",
                             "price":35.00,
                             "maxChoices":1,
                             "position":1000,
                             "visible":1,
                             "availabilityType":"AVAILABLE_NOW",
                             "qty":1,
                             "available":true
                          },
                          {
                             "id":7476056,
                             "name":"3 meats",
                             "price":37.00,
                             "maxChoices":1,
                             "position":2000,
                             "visible":1,
                             "availabilityType":"AVAILABLE_NOW",
                             "available":true
                          }
                       ]
                    }
                 ],
                 "images":[
                    {
                       "id":108307,
                       "image":"https://preodemo.gumlet.io/usr/venue/7602/menuItem/646fbe01b3373.png"
                    }
                 ],
                 "available":true
              },
              {
                 "id":1625703,
                 "name":"Ogro Burger",
                 "description":"180g angus beef burger, homemade molasses barbecue with golden bacon cubes, mozzarella cheese and homemade roasted garlic mayonnaise.",
                 "alcoholic":0,
                 "price":33.00,
                 "position":2000,
                 "visible":1,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1625703",
                 "images":[
                    {
                       "id":108309,
                       "image":"https://preodemo.gumlet.io/usr/venue/7602/menuItem/646fbe292998e.png"
                    }
                 ],
                 "available":true
              }
           ]
        },
        {
           "id":242404,
           "name":"Drinks",
           "position":1000,
           "visible":1,
           "images":[
              {
                 "id":1551,
                 "image":"https://preodemo.gumlet.io/usr/venue/7602/section/646fbe5dc1bf3.png"
              }
           ],
           "items":[
              {
                 "id":1625705,
                 "name":"Caipirinha",
                 "alcoholic":0,
                 "price":13.00,
                 "position":0,
                 "visible":1,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1625705",
                 "available":true
              },
              {
                 "id":1004123,
                 "name":"Red Label",
                 "alcoholic":0,
                 "price":13.00,
                 "position":1000,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1004123",
                 "available":true
              },
              {
                 "id":1004122,
                 "name":"Smirnoff",
                 "alcoholic":0,
                 "price":10.00,
                 "position":2000,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1004122",
                 "available":true
              },
              {
                 "id":1625706,
                 "name":"Pink Lemonade",
                 "alcoholic":0,
                 "price":12.00,
                 "position":3000,
                 "availabilityType":"AVAILABLE_NOW",
                 "sku":"I1004123",
                 "available":true
              }
           ]
        },
        {
           "id":242677,
           "name":"Desserts",
           "position":2000,
           "images":[
              {
                 "id":1552,
                 "image":"https://preodemo.gumlet.io/usr/venue/7602/section/646fbe93cb615.png"
              }
           ],
           "items":[
              {
                 "id":1625704,
                 "name":"Nutella",
                 "alcoholic":0,
                 "price":18.90,
                 "position":0,
                 "visible":1,
                 "availabilityType":"AVAILABLE_NOW",
                 "images":[
                    {
                       "id":108310,
                       "image":"https://preodemo.gumlet.io/usr/venue/7602/menuItem/646fbf0bec8fe.png"
                    }
                 ],
                 "available":true
              }
           ]
        }
     ]
  }
```

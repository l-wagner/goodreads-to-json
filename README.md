# goodreads-to-json
Python script to pull a user's read books from Goodreads into a json file.


## How to
1. Clone repo. 
2. Prep environment:

        $ python3 -m venv venv
        $ source venv/bin/activate
        $ pip install -r requirements.txt
3. Fill config.json with your [Goodreads API Key](https://www.goodreads.com/api) and the [user id](https://help.goodreads.com/s/article/Where-can-I-find-my-user-ID) of whoever's read shelf you are interested in. 
4. Run!

       $ python goodreads_parser.py
    
 ### Output

     [
      {
        "title": "Gingerbread",
        "author": "Helen Oyeyemi",
        "year": "2019",
        "imageUrl": "https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1549556368l/40634915._SX98_.jpg",
        "link": "https://www.goodreads.com/book/show/40634915-gingerbread",
        "averageRating": "3.05",
        "rating": "5"
      },
      {
        "title": "Set This House in Order",
        "author": "Matt Ruff",
        "year": "2004",
        "imageUrl": "https://s.gr-assets.com/assets/nophoto/book/111x148-bcc042a9c91a29c1d680899eff700a03.png",
        "link": "https://www.goodreads.com/book/show/71847.Set_This_House_in_Order",
        "averageRating": "4.29",
        "rating": "5"
      }
    ]

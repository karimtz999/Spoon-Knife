def getDaapoint(qoute):
    stock = quote['stock']
    bid_price = floate(qoute['top_bid']['price'])
    ask_price = floate(qoute['top_ask']['price'])
    price = (bid_price + ask_price)/2
    return stock, bid_price, ask_price, price

def getRatio(price_a, price_b):
    if(price_b == 0):
        return
    return price_a/price_b

#main

if __name__ == "__main__":
    for  __ in iter(range(N)):
    quotes = json.loads(urllib.request.urllopen(query.format(random.random())).read)
    prices = {}
    for qoute in qoutes:
        stock,bid_price,ask_price = getDaraPoint(qoute)
        print("qouted %s at (bid: %s , ask: %s , price: %s)"%(stock,bid_price, ask_price, price))

    print("Ratio %s" % grtRatio(prices["ABC"], prices["DFE"]))
    

MySQL clobs come back from the driver as binary data, so we need to make a subclass that knows it needs a converter for its incoming data.
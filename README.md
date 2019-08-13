# electricity_pricing

track Illinois' time-dependent electricity pricing
5minute api accepts time params as:
  yyyyMMddhhmm in CST (UTC? I dunno it doesn't really return the requested range...)

api returns times UTC millis, but only historical, most recent is like 10 minutes ago, no future or current

pretty sure comed charges by hourly average price

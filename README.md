# electricity_pricing

track Illinois' (ComEd) time-dependent electricity pricing
5-minute api accepts time params as:
  yyyyMMddhhmm in local time

api returns times in UTC millis, but only historical, most recent is like 10 minutes ago, no future or current

pretty sure ComEd charges by hourly average price

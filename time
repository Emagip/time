from datetime import datetime 
from pytz import timezone 
  
format = "nous sommes le %Y %m %d et il est %H:%M"
  
# Current time in UTC 
now_utc = datetime.now(timezone('UTC')) 
  
# Convert to Asia/Kolkata time zone 
now_paris = now_utc.astimezone(timezone('Europe/Paris')) 
print(now_paris.strftime(format)) 

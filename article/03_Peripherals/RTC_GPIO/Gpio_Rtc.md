# Real-time Clock (RTC)

### Backup Power Domain
1. What 
2. Why
    
### Calibration
   1. Princeple
   2. How to use
    
### RTC usage | C Date And Time Function In DLib
  - >time_t time(time_t *) ;    
  - >__DEPREC_ATTRS char *          asctime(const struct tm *);    
  - > __ATTRIBUTES   clock_t         clock(void);    
  - >__DEPREC_ATTRS char *          ctime(const time_t *);    
  - >__EFF_NE __ATTRIBUTES double   difftime(time_t, time_t);    
  - >__DEPREC_ATTRS struct tm *     gmtime(const time_t *);    
  - >__DEPREC_ATTRS struct tm *     localtime(const time_t *);    
  - > __ATTRIBUTES   time_t          mktime(struct tm *);    
  - >__ATTRIBUTES   int             timespec_get(struct timespec *, int);       



## Refrence
[1] [https://pubs.opengroup.org/onlinepubs/009695399/functions/time.htm)](https://pubs.opengroup.org/onlinepubs/009695399/functions/time.htm)




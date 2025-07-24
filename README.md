# trickcal-couponstance

## Changelog
1. Adding .env and support multiple UID in single run
2. Adding mechanism to check local latest coupon, so you can put into cron and don't repeated submit the coupon.
3. Adding logging to check if anything wrong on the runtime

Required to Run below first
### .env File
Input your UID or multiple UID in .env (Please read the comment on .env)
### Playwright Install
```bash
playwright install chromium
```
### And run as usual
```python
python couponstance.py
```
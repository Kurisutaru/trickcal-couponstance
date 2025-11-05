# Trickcal Coupon Stance

## Changelog
1. [NEW] Parsing coupon mechanism, thanks to Author of [Trickcal Alarm](https://github.com/ngvf1222/Trickcal_alarm) for the Naver feed url !
2. Adding feature to Post Discord Webhook
3. Adding things to make playwright behavior like real human on top of humanizer script (maybe work, maybe not)
4. Retry on failed input coupon
5. Log Rotation every sunday

## Pre-Changelog
1. Adding .env and support multiple UID in single run
2. Adding mechanism to check local latest coupon, so you can put into cron and don't repeated submit the coupon.
3. Adding logging to check if anything wrong on the runtime

Required to Run below first
### .env File
Input your UID or multiple UID in .env (Please read the comment on .env)
### UV / pip
```bash
uv sync
```
or
```bash
pip install -r requirements.txt
```
### Playwright Install
```bash
playwright install chromium
```
### And run as usual
```bash
python couponstance.py
```
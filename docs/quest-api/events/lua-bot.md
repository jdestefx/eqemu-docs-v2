## EVENT_AGGRO_SAY

``` lua

function EVENT_AGGRO_SAY(e) {
}
```
## EVENT_CAST

``` lua

function EVENT_CAST(e) {
	eq.debug("spell " .. e.spell);
	eq.debug("caster_id " .. e.caster_id);
	eq.debug("caster_level " .. e.caster_level);
}
```
## EVENT_CAST_BEGIN

``` lua

function EVENT_CAST_BEGIN(e) {
	eq.debug("spell " .. e.spell);
	eq.debug("caster_id " .. e.caster_id);
	eq.debug("caster_level " .. e.caster_level);
}
```
## EVENT_CAST_ON

``` lua

function EVENT_CAST_ON(e) {
	eq.debug("spell " .. e.spell);
	eq.debug("caster_id " .. e.caster_id);
	eq.debug("caster_level " .. e.caster_level);
}
```
## EVENT_COMBAT

``` lua

function EVENT_COMBAT(e) {
	eq.debug("other " .. e.other);
	eq.debug("joined " .. e.joined);
}
```
## EVENT_DEATH

``` lua

function EVENT_DEATH(e) {
	eq.debug("other " .. e.other);
	eq.debug("damage " .. e.damage);
	eq.debug("spell " .. e.spell);
	eq.debug("skill " .. e.skill);
}
```
## EVENT_DEATH_COMPLETE

``` lua

function EVENT_DEATH_COMPLETE(e) {
	eq.debug("other " .. e.other);
	eq.debug("damage " .. e.damage);
	eq.debug("spell " .. e.spell);
	eq.debug("skill " .. e.skill);
}
```
## EVENT_PAYLOAD

``` lua

function EVENT_PAYLOAD(e) {
	eq.debug("payload_id " .. e.payload_id);
	eq.debug("payload_value " .. e.payload_value);
}
```
## EVENT_POPUP_RESPONSE

``` lua

function EVENT_POPUP_RESPONSE(e) {
	eq.debug("other " .. e.other);
	eq.debug("popup_id " .. e.popup_id);
}
```
## EVENT_SAY

``` lua

function EVENT_SAY(e) {
	eq.debug("other " .. e.other);
	eq.debug("message " .. e.message);
	eq.debug("language " .. e.language);
}
```
## EVENT_SIGNAL

``` lua

function EVENT_SIGNAL(e) {
	eq.debug("signal " .. e.signal);
}
```
## EVENT_SLAY

``` lua

function EVENT_SLAY(e) {
	eq.debug("other " .. e.other);
}
```
## EVENT_SPAWN

``` lua

function EVENT_SPAWN(e) {
}
```
## EVENT_TARGET_CHANGE

``` lua

function EVENT_TARGET_CHANGE(e) {
	eq.debug("other " .. e.other);
}
```
## EVENT_TIMER

``` lua

function EVENT_TIMER(e) {
	eq.debug("timer " .. e.timer);
}
```
## EVENT_TRADE

``` lua

function EVENT_TRADE(e) {
	eq.debug("other " .. e.other);
	eq.debug("platinum " .. e.platinum);
	eq.debug("gold " .. e.gold);
	eq.debug("silver " .. e.silver);
	eq.debug("copper " .. e.copper);
	eq.debug("trade " .. e.trade);
}
```
## EVENT_USE_SKILL

``` lua

function EVENT_USE_SKILL(e) {
}
```
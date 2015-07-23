# craft-bed

Parameterized bed model.

### Usage
```html
<craft>
    <craft name="bed" module="craft-bed"/>
    <bed></bed>
</craft>
```

### Parameters
- width: adjusts width of bed 
    - default: 40
- length: adjusts length of bed
    - default: 75
- mattressHeight: adjusts height of mattress
    - default: 10
- legHeight: adjusts height of frame legs
    - default: 8
- headRound: adjusts between rounded and standard headboard
    - 0 = standard, 1 = rounded (default)
- bedFrame: adjusts between mattress only and mattress + frame
    - 0 = mattress, 1 = mattress + frame (default)

### Example
```html
<craft>
    <craft name="bed" module="craft-bed"/>
    <row spacing="2">
        <bed width="76" length="40" headRound="0"></bed>
        <bed></bed>
    </row>
</craft>
```

![example](example.png)

NationStates card data dump in raw XML instead of GZ format.

XML Format:

```
<CARDS>
    <SET>
        <SEASON>
        <CARD>
            <ID>INTEGER</ID>
            <NAME>STRING</NAME>
            <TYPE>STRING</NAME>
            <MOTTO>STRING</NAME>
            <CATEGORY>STRING</NAME>
            <REGION>STRING</NAME>
            <FLAG>https://www.nationstates.net/images/cards/s{SEASON}/{URL}</FLAG>
            <BANNER>https://www.nationstates.net/images/cards/s4/banners/{URL}</BANNER> <- S4 ONLY
            <CARDCATEGORY>STRING</CARDCATEGORY>
            <DESCRIPTION>
            <BADGES>
                <BADGE>STRING</BADGE>
                ...
            </BADGES>
            <TROPHIES>
                <TROPHY type=string></TROPHY>
                ...
            </TROPHIES>
        </CARD>
        ...
    </SET>
</CARDS>
```

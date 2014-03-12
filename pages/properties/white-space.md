---

property: white-space

introduced: CSS1

support:
    firefox: 1
    safari: 1
    opera: 4
    chrome: 1
    ie: 5.5

values:
    normal:
    nowrap:
    pre:
        support:
            firefox: 1
            safari: 1
            opera: 4
            chrome: 1
            ie: 6
    pre-wrap:
        introduced: CSS2.1
        support:
            firefox: [1, 3]
            safari: 1
            opera: [4, 8]
            chrome: 1
            ie: 8
    pre-line:
        introduced: CSS2.1
        support:
            firefox: 3.5
            safari: 1
            opera: 9.5
            chrome: 1
            ie: 8

---

## Specifications

1. [CSS Text Level 4](http://dev.w3.org/csswg/css-text-4/#white-space) [Editor’s Draft]
2. [CSS Text Level 3](http://dev.w3.org/csswg/css-text/#white-space) [Editor’s Draft]
3. [CSS Level 2 Revision 1, Text](http://www.w3.org/TR/CSS2/text.html#propdef-white-space) [Recommendation]
4. [CSS Level 1, Text](http://www.w3.org/TR/REC-CSS1/#white-space) [Recommendation]
{:.specs}

## Prefixes

- Firefox required the `-moz-` prefix on the value for `pre-wrap`, until it was supported prefixless in Firefox 3. Support for `-moz-pre-wrap` was dropped after Firefox 3.5.
- Opera originally supported `pre-wrap` as `-pre-wrap` from Opera 4.x until 6.x. This was updated to `-o-pre-wrap` in Opera 7. The unprefixed version has been supported since Opera 8.
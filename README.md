# WhiteCss
WhiteCSS is CSS utility framework, whitecss provides many usable class utilities for margin, padding, border, font, color etc.

#### Using npm
> `npm install whitecss --save`

#### Using bower
> `bower install whitecss --save`


### Utilities

- [x] [Margin](#1-margin)
- [x] [Padding] (#2-padding)
- [x] [Font] (#3-font)
- [x] [Border] (#4-border)
- [x] [Color] (#5-color)
- [x] [Position] (#6-position)
- [x] [Width] (#7-width)
- [x] [Typography] (#8-typography)
- [x] [Colors] (#9-colors)


#### 1. Margin

| CLASS  | STYLE |
|---| --- |
|  .m-xxs  | margin: 2px |
|  .m-xs   | margin: 5px |
|  .m-sm   | margin: 10px |
|  .m-md   | margin: 15px |
|  .m-lg   | margin: 30px |
|  .m-xlg  | margin: 50px |
|  .m-xxlg | margin: 100px |
|  .m-none | margin: 0 |
|  .m-t-none | margin-top: 0 |
|  .m-r-none | margin-right: 0 |
|  .m-b-none | margin-bottom: 0 |
|  .m-l-none | margin-left: 0 |
|  .m-x-none | margin-left: 0; margin-right: 0 |
|  .m-y-none | margin-top: 0; margin-bottom: 0 |
| --- | --- |
|  .m-auto | margin: auto |
|  .m-l-auto | margin-left: auto |
|  .m-r-auto | margin-right: auto |
|  .m-x-auto | margin-left: auto; margin-right: auto |

| CLASS  | STYLE |
|---| --- |
|  .m-t-sm  | margin-top: 10px |
|  .m-r-sm  | margin-right: 10px |
|  .m-b-sm  | margin-bottom: 10px |
|  .m-l-sm  | margin-left: 10px |
|  .m-x-sm  | margin-left: 10px, margin-right: 10px |
|  .m-y-sm  | margin-top: 10px, margin-bottom: 10px |

> Same classes works for `xss,xs,md,lg,xlg,xxlg` just replace suffix with `sm`


#### 2. Padding

| CLASS  | STYLE |
|---| --- |
|  .p-xxs  | padding: 2px |
|  .p-xs   | padding: 5px |
|  .p-sm   | padding: 10px |
|  .p-md   | padding: 15px |
|  .p-lg   | padding: 30px |
|  .p-xlg  | padding: 50px |
|  .p-xxlg | padding: 100px |
|  .p-none | padding: 0 |
|  .p-t-none | padding-top: 0 |
|  .p-r-none | padding-right: 0 |
|  .p-b-none | padding-bottom: 0 |
|  .p-l-none | padding-left: 0 |
|  .p-x-none | padding-left: 0; padding-right: 0 |
|  .p-y-none | padding-top: 0; padding-bottom: 0 |

| CLASS  | STYLE |
|---| --- |
|  .p-t-sm  | padding-top: 10px |
|  .p-r-sm  | padding-right: 10px |
|  .p-b-sm  | padding-bottom: 10px |
|  .p-l-sm  | padding-left: 10px |
|  .p-x-sm  | padding-left: 10px, padding-right: 10px |
|  .p-y-sm  | padding-top: 10px, padding-bottom: 10px |

> Same classes works for `xss,xs,md,lg,xlg,xxlg` just replace suffix with `sm`

#### 3. Font
| CLASS  | STYLE |
|---| --- |
|  .font-xs,   .h6  | font-size: 12px |
|  .font-sm,   .h5  | font-size: 14px |
|  .font-md,   .h4  | font-size: 18px |
|  .font-lg,   .h3  | font-size: 24px |
|  .font-xlg,  .h2  | font-size: 30px  |
|  .font-xxlg, .h1  | font-size: 36px  |
|  .text-primary    | color: #2e6da4   |
|  .text-success    | color: #398439   |
|  .text-default    | color: #cccccc   |
|  .text-info       | color: #269abc   |
|  .text-warning    | color: #d58512   |
|  .text-danger     | color: #d43f3a   |


#### 4. Border

| CLASS  | STYLE |
|---| --- |
| .b    | border-width: 1px |
| .b-t  | border-top-width: 1px |
| .b-r  | border-right-width: 1px |
| .b-b  | border-bottom-width: 1px |
| .b-l  | border-left-width: 1px |
| .b-primary  | border-color: #2e6da4 |
| .b-success  | border-color: #398439 |
| .b-default  | border-color: #cccccc |
| .b-info     | border-color: #269abc |
| .b-warning  | border-color: #d58512 |
| .b-danger   | border-color: #d43f3a |

#### 5. Color

| CLASS  | STYLE |
|---| --- |
| .bg-primary  | background-color: #2e6da4 |
| .bg-success  | background-color: #398439 |
| .bg-default  | background-color: #cccccc |
| .bg-info     | background-color: #269abc |
| .bg-warning  | background-color: #d58512 |
| .bg-danger   | background-color: #d43f3a |

#### 6. Position

| CLASS  | STYLE |
|---| --- |
| .p-relative  | position: relative |
| .p-absolute  | position: absolute |
| .p-fixed     | position: fixed    |
| .p-static    | position: static   |

#### 7. Width

| CLASS  | STYLE |
|---| --- |
| .w-10  | width: 10% !important |
| .w-20  | width: 20% !important |
| .w-25  | width: 25% !important |
| .w-30  | width: 30% !important |
| .w-40  | width: 40% !important |
| .w-50  | width: 50% !important |
| .w-60  | width: 60% !important |
| .w-70  | width: 70% !important |
| .w-75  | width: 75% !important |
| .w-80  | width: 80% !important |
| .w-90  | width: 90% !important |
| .w-100  | width: 100% !important |
| ---  | --- |
| .w-xss  | width: 50px !important |
| .w-xs  | width: 100px !important |
| .w-sm  | width: 150px !important |
| .w-md  | width: 300px !important |
| .w-lg  | width: 500px !important |
| .w-xlg  | width: 750px !important |
| .w-xxlg  | width: 900px !important |

#### 8. Typography

| CLASS  | STYLE |
|---| --- |
|.t-bold |  font-weight: bold;  |
|.t-regular |  font-weight: 400;  |
|.t-italic |  font-style: italic;  |
|.t-capital | text-transform: uppercase;  letter-spacing: .25em;  |
|.t-left | text-align: left  |
|.t-center | text-align: center  |
|.t-right | text-align: right  |
|.t-justify | text-align: justify  |
|.t-no-wrap | white-space: nowrap  |
|.t-underline | text-decoration: underline  |
|.t-deco-none | text-decoration: none  |

#### 9. Colors

| CLASS  | VALUE |
|---| --- |
|.c-alice-blue | 	{color: #f0f8ff;} |
|.c-antique-white  | 	{color: #faebd7;} |
|.c-aqua	 | 	{color: #00ffff;} |
|.c-aquamarine| 	{color: #7fffd4;} |
|.c-azure	 | 	{color: #f0ffff;} |
|.c-beige	 | 	{color: #f5f5dc;} |
|.c-bisque	 | 	{color: #ffe4c4;} |
|.c-black	 | 	{color: #000000;} |
|.c-blanched-almond| 	{color: #ffebcd;} |
|.c-blue	 | 	{color: #0000ff;} |
|.c-blue-violet  | 	{color: #8a2be2;} |
|.c-brown	 | 	{color: #a52a2a;} |
|.c-burly-wood| 	{color: #deb887;} |
|.c-cadet-blue| 	{color: #5f9ea0;} |
|.c-chartreuse| 	{color: #7fff00;} |
|.c-chocolate| 	{color: #d2691e;} |
|.c-coral	 | 	{color: #ff7f50;} |
|.c-cornflower-blue| 	{color: #6495ed;} |
|.c-cornsilk| 	{color: #fff8dc;} |
|.c-crimson	 | 	{color: #dc143c;} |
|.c-cyan	 | 	{color: #00ffff;} |
|.c-dark-blue| 	{color: #00008b;} |
|.c-dark-cyan| 	{color: #008b8b;} |
|.c-dark-golden-rod| 	{color: #b8860b;} |
|.c-dark-gray| 	{color: #a9a9a9;} |
|.c-dark-grey| 	{color: #a9a9a9;} |
|.c-dark-green| 	{color: #006400;} |
|.c-dark-khaki| 	{color: #bdb76b;} |
|.c-dark-magenta| 	{color: #8b008b;} |
|.c-dark-olive-green| 	{color: #556b2f;} |
|.c-dark-orange| 	{color: #ff8c00;} |
|.c-dark-orchid| 	{color: #9932cc;} |
|.c-dark-red	 | 	{color: #8b0000;} |
|.c-dark-salmon| 	{color: #e9967a;} |
|.c-dark-sea-green| 	{color: #8fbc8f;} |
|.c-dark-slate-blue| 	{color: #483d8b;} |
|.c-dark-slate-gray| 	{color: #2f4f4f;} |
|.c-dark-slate-grey| 	{color: #2f4f4f;} |
|.c-dark-turquoise| 	{color: #00ced1;} |
|.c-dark-violet| 	{color: #9400d3;} |
|.c-deep-pink| 	{color: #ff1493;} |
|.c-deep-sky-blue| 	{color: #00bfff;} |
|.c-dim-gray	 | 	{color: #696969;} |
|.c-dim-grey	 | 	{color: #696969;} |
|.c-dodger-blue| 	{color: #1e90ff;} |
|.c-fire-brick| 	{color: #b22222;} |
|.c-floral-white| 	{color: #fffaf0;} |
|.c-forest-green| 	{color: #228b22;} |
|.c-fuchsia	 | 	{color: #ff00ff;} |
|.c-gainsboro| 	{color: #dcdcdc;} |
|.c-ghost-white| 	{color: #f8f8ff;} |
|.c-gold	 | 	{color: #ffd700;} |
|.c-golden-rod| 	{color: #daa520;} |
|.c-gray	 | 	{color: #808080;} |
|.c-grey	 | 	{color: #808080;} |
|.c-green	 | 	{color: #008000;} |
|.c-green-yellow| 	{color: #adff2f;} |
|.c-honey-dew| 	{color: #f0fff0;} |
|.c-hot-pink	 | 	{color: #ff69b4;} |
|.c-indian-red| 	{color: #cd5c5c;} |
|.c-indigo	 | 	{color: #4b0082;} |
|.c-ivory	 | 	{color: #fffff0;} |
|.c-khaki	 | 	{color: #f0e68c;} |
|.c-lavender| 	{color: #e6e6fa;} |
|.c-lavender-blush| 	{color: #fff0f5;} |
|.c-lawn-green| 	{color: #7cfc00;} |
|.c-lemon-chiffon| 	{color: #fffacd;} |
|.c-light-blue| 	{color: #add8e6;} |
|.c-light-coral| 	{color: #f08080;} |
|.c-light-cyan| 	{color: #e0ffff;} |
|.c-light-golden-rod-yellow	 {color: #fafad2;} |
|.c-light-gray| 	{color: #d3d3d3;} |
|.c-light-grey| 	{color: #d3d3d3;} |
|.c-light-green| 	{color: #90ee90;} |
|.c-light-pink| 	{color: #ffb6c1;} |
|.c-light-salmon| 	{color: #ffa07a;} |
|.c-light-sea-green| 	{color: #20b2aa;} |
|.c-light-sky-blue| 	{color: #87cefa;} |
|.c-light-slate-gray| 	{color: #778899;} |
|.c-light-slate-grey| 	{color: #778899;} |
|.c-light-steel-blue| 	{color: #b0c4de;} |
|.c-light-yellow| 	{color: #ffffe0;} |
|.c-lime	 | 	{color: #00ff00;} |
|.c-lime-green| 	{color: #32cd32;} |
|.c-linen	 | 	{color: #faf0e6;} |
|.c-magenta	 | 	{color: #ff00ff;} |
|.c-maroon	 | 	{color: #800000;} |
|.c-medium-aqua-marine{color: #66cdaa;} |
|.c-medium-blue| 	{color: #0000cd;} |
|.c-medium-orchid| 	{color: #ba55d3;} |
|.c-medium-purple| 	{color: #9370db;} |
|.c-medium-sea-green| 	{color: #3cb371;} |
|.c-medium-slate-blue| 	{color: #7b68ee;} |
|.c-medium-spring-green {color: #00fa9a;} |
|.c-medium-turquoise| 	{color: #48d1cc;} |
|.c-medium-violet-red| 	{color: #c71585;} |
|.c-midnight-blue| 	{color: #191970;} |
|.c-mint-cream| 	{color: #f5fffa;} |
|.c-misty-rose| 	{color: #ffe4e1;} |
|.c-moccasin| 	{color: #ffe4b5;} |
|.c-navajo-white| 	{color: #ffdead;} |
|.c-navy	 | 	{color: #000080;} |
|.c-old-lace	 | 	{color: #fdf5e6;} |
|.c-olive	 | 	{color: #808000;} |
|.c-olive-drab| 	{color: #6b8e23;} |
|.c-orange	 | 	{color: #ffa500;} |
|.c-orange-red| 	{color: #ff4500;} |
|.c-orchid	 | 	{color: #da70d6;} |
|.c-pale-golden-rod| 	{color: #eee8aa;} |
|.c-pale-green| 	{color: #98fb98;} |
|.c-pale-turquoise| 	{color: #afeeee;} |
|.c-pale-violet-red| 	{color: #db7093;} |
|.c-papaya-whip| 	{color: #ffefd5;} |
|.c-peach-puff| 	{color: #ffdab9;} |
|.c-peru	 | 	{color: #cd853f;} |
|.c-pink	 | 	{color: #ffc0cb;} |
|.c-plum	 | 	{color: #dda0dd;} |
|.c-powder-blue| 	{color: #b0e0e6;} |
|.c-purple	 | 	{color: #800080;} |
|.c-rebecca-purple| 	{color: #663399;} |
|.c-red	| 	{color: #ff0000;} |
|.c-rosy-brown| 	{color: #bc8f8f;} |
|.c-royal-blue| 	{color: #4169e1;} |
|.c-saddle-brown| 	{color: #8b4513;} |
|.c-salmon	 | 	{color: #fa8072;} |
|.c-sandy-brown| 	{color: #f4a460;} |
|.c-sea-green| 	{color: #2e8b57;} |
|.c-sea-shell| 	{color: #fff5ee;} |
|.c-sienna	 | 	{color: #a0522d;} |
|.c-silver	 | 	{color: #c0c0c0;} |
|.c-sky-blue	 | 	{color: #87ceeb;} |
|.c-slate-blue| 	{color: #6a5acd;} |
|.c-slate-gray| 	{color: #708090;} |
|.c-slate-grey| 	{color: #708090;} |
|.c-snow	 | 	{color: #fffafa;} |
|.c-spring-green| 	{color: #00ff7f;} |
|.c-steel-blue| 	{color: #4682b4;} |
|.c-tan	 | 	{color: #d2b48c;} |
|.c-teal	 | 	{color: #008080;} |
|.c-thistle	 | 	{color: #d8bfd8;} |
|.c-tomato	 | 	{color: #ff6347;} |
|.c-turquoise| 	{color: #40e0d0;} |
|.c-violet	 | 	{color: #ee82ee;} |
|.c-wheat	 | 	{color: #f5deb3;} |
|.c-white	 | 	{color: #ffffff;} |
|.c-white-smoke| 	{color: #f5f5f5;} |
|.c-yellow	 | 	{color: #ffff00;} |
|.c-yellow-green| 	{color: #9acd32;} |

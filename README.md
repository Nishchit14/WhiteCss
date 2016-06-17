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
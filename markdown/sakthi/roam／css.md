- ```css
@imprt url("https://linuz90.github.io/better-roam-research/dark.css");
textarea,
div,
textarea {
  font-family: 'Roboto';
  font-size: inherit;
}```
- ```css
    /* Page Ref link Color */
/*span.rm-page-ref {
    color: #95B4CE !important;
    //background-color:  #2C2C2C;
    border: 1px #FFFFFF;
    border-radius: 1px;
    padding: 1px 1px;
}*/
    /* # tag Page Link color */
span.rm-page-ref[data-tag] {
    color: #000000B2 !important;
    background-color:  #E8E8E8;
    border: 1px #FFFFFF;
    border-radius: 1px;
    padding: 1px 1px;
} 
    /* # tag (starts with :) Page Link color  */
span.rm-page-ref[data-tag^=":"] {
    color: #FBFBFBEE !important;
    background-color:  #FB0000ff;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="-"] {
    color: #FBFBFBEE !important;
    background-color:  #5716CAff;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag$="it"] {
    color: #FBFBFBEE !important;
    background-color:  #5716CAff;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="^"] {
    color: #FDFBFBEE !important;
    background-color:  #607D8Bbb;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="'"] {
    color: #FDFBFBEE !important;
    background-color:  #9C27B0bb;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="&"] {
    color: #FDFBFBEE !important;
    background-color:  #795548bb;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="/"] {
    color: #FFFFFFFF !important;
    background-color:  #000000dd;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="$"] {
    color: #FFFFFFFF !important;
    background-color:  #E91E63dd;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="="] {
    color: #FFFFFFFF !important;
    background-color:  #FF9800dd;
    border: 1px #FFFFFF;
    border-radius: 3px;
    padding: 3px 6px;
}
    /* Other # tag color */
span.rm-page-ref[data-tag="inbox"] {
    color: #F9F9F9ff !important;
    background-color:  #F40808;
    border: 1px #F20000bb;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="?"] {
    color: #ffffffCC !important;
    background-color:  #1297ff;
    border: 1px #ffffff;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag^="my"] {
    color: #FDFDFDcc !important;
  	background-color:  #009688;
    border: 1px #009688;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag="evergreen"] {
    color: #ffffffcc !important;
    background-color:  #02B30Aee;
    border: 1px #ffffff;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag="outline"] {
    color: #ffffffcc !important;
    background-color:  #02B30Aee;
    border: 1px #ffffff;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag="Project"] {
    color: #ffffffcc !important;
    background-color:  #A46D08;
    border: 1px #ffffff;
    border-radius: 3px;
    padding: 3px 6px;
}
span.rm-page-ref[data-tag="outbox"] {
    color: #ffffffcc !important;
    background-color:  #FE04B9;
    border: 1px #ffffff;
    border-radius: 3px;
    padding: 3px 6px;
}```
- Custom Tags Theming 

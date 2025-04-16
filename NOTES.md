Element change for color of context menu items in vencord theme.




Context menu bug:
neutron.css:3453
12633.ce693...3ed.css:503

element.style {
}
:where(.visual-refresh) .colorDefault_c1e9c4 .label_c1e9c4 {
    color: var(--themeColor1);
}
:where(.visual-refresh) .colorDefault_c1e9c4 .label_c1e9c4 {
    /* color: var(--header-primary); */
}


My account Settings Menu fix:
neutron8.css:3473
.field__1fed1 {
    background-color: var(--backgroundColor);
}



New Radial Status Repository here: https://github.com/DiscordStyles/RadialStatus/tree/master




Download background fix not black block anymore:
.fileWrapper__0ccae, .embedFull__623de, .wrapper_d5f3cd { background: var(--custom-settings-menu-myaccount-background-color);}



download button fix:

.nonMediaMosaicItem__06ab4 {
    outline: 1px solid var(--background-secondary);
    right: 2px;
    top: 2px;
    width: 102px;
    height: 71px;
}


.fileWrapper__0ccae > *, .wrapper_d5f3cd > * {
    z-index: 0;
    position: relative;
}



.nonMediaMosaicItem__06ab4 {
    outline: 1px solid var(--background-secondary);
    right: -325px;
    top: -68px;
    width: 102px;
    height: 62px;
}





button actually inner:
.hoverButton__06ab4 {
    color: var(--interactive-normal);
    cursor: pointer;
    display: flex;
    padding: 6px;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    align-content: center;
}
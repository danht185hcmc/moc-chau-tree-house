Sắp xếp code thêm nhóm

    // Layout properties
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;

    // Position properties
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;

    // Box model properties
    width: 100px;
    height: 200px;
    padding: 10px 0;
    margin: 0 10px;

    // Visual Properties
    background: $white;
    color: $primary;
    border: 1px solid $dark-1;
    border-radius: 10px;
    outline: 0;
    box-shadow: 0 5px 0 $white;

    // Typography properties
    font-family: $font-base;
    font-size: $font-size-base;
    font-weight: bold;
    line-height: 1.5;
    text-align: center;
    text-transform: uppercase;

    // Mics properties
    cursor: pointer;
    overflow: auto;
    z-index: 9;

    // CSS3 properties
    transform: scale(2);
    transition: all .3s;

    // Pseudo class
    &:hover {}

    &:after {}

    &:before {}

    &:first-child {}

    &:last-child {}

    // Breakpoint sorted descending
    @media screen and (max-width: 1200px) {}

    @media screen and (max-width: 992px) {}

    @media screen and (max-width: 767px) {}

    // Selector
    &\_\_list {}

    .selector {}
    }

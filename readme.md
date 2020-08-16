# exercise to understand Css grid.
Conceptually it is similar to an old table lyout but can use semantic HTML elements with a more flexible layout.

#Html Parts
##.container: 
It is the global wrapper, it has small margins to the left and right.//also used .body
##.Main-Header: 
is the header contains .logo(20%, float to left) .main-menu(Ocupies 79%, floats to right).
##.content-area-wrapper: 
Wraps the main .content-area (66.6%, minus 1rem for margin, float to left) and the .sidebar(33.3%, floats to the right)
##.sponsors-wrapper: 
contains the sponsors logos. There is a .sponsors section with te display property set table. Each sporsor is
displayed as a table cell.
##.footer:
It is our footer and spans to 100% of space 
#Making the layout responsive
With Grid is very easy to do responsiveness because we can easyly reposisioned the areas.
## screens
We'll be use the same breakepoins as bootstrap 4
1.  Extra large = > 1140px  xl
2.  large       = > 992px   lg
3.  Medium      = > 768px   md
4.  Small       = > 1140px  sm

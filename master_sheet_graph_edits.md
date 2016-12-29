## MASTER SHEET FOR ALL EDITS MADE IN LUMINA GRAPHS

#SECTION 1: WHAT IS COLLEGE


#SECTION 2: COST OF EDUCATING

*Figure 2-7: for all multiples, add spaces to x-axis labels to create two lines, for example: "'01'–        '02'"

**Figure 2-51: Change Y-axis properties to adjust ticks:
  "axis": {
    "y": {
        "max": 6000,
      "padding": {"top": 0, "bottom": 0},
      "tick": {
        "format": "dollar",
        "count": 4
      }
    },
**Figure 2-52: Change Y-axis properties to adjust ticks:
  "axis": {
    "y": {
    "max": 1000,
    "padding": {"top": 0, "bottom": 0},
      "tick": {
        "format": "dollar",
        "count": 5

      }
    },
**Figure 2-53: Change Y-axis properties to adjust ticks:
    "y": {
   "max": 60000,
    "padding": {"top": 0, "bottom": 0},
      "tick": {
        "format": "dollar",
        "count": 4

      }
    }
**Figure 2-54: Change Y-axis properties to adjust ticks:
    "y": {
        "max": 4000,
         "padding": {"top": 0, "bottom": 0},
      "tick": {
        "format": "dollar",
        "count": 5
      }
    }
    
**Figure 2-55: Change Y-axis properties to adjust ticks:
    "y": {
        "max": 30000,
        "padding": {"top": 0, "bottom": 0},

      "tick": {
        "format": "dollar",
        "count": 4
      }
    },

**Figure 2-61: Change Y-axis properties to adjust ticks:
    "y": {
      "padding": {"top": 0, "bottom": 0},
      "max": 20000,
      "tick": {
        "format": "dollar",
        "count": 5
      }
    }
**Figure 2-62: Change Y-axis properties to adjust ticks:
        "y": {
     "padding": {"top": 0, "bottom": 0},
     "max": 1000,
      "tick": {
        "format": "dollar",
        "count": 5
      }
    }

#SECTION 3: PRICES AND EXPENSES

**Figure 3-3 (all multiples): manually change color for each to avoid automated repeating colors
"colors": {
    "Lowest decile": "#1696D2", 
    "2nd":"#000000", 
    "3rd":"#FDBF11", 
    "4th": "#55b748", 
    "5th":"#d2d2d2", 
    "6th": "#ec008b", 
    "7th": "#cb9f5b", 
    "8th": "#7348b7", 
    "9th": "#ff0000", 
    "Highest decile": "#0f658d"
   }

**Figure 3-18: 
Set max value and change number of ticks for 81 and 82
"y": {
      "padding": {"top": 0, "bottom": 0},
      "max": 60000,
      "tick": {
        "format": "dollar",
        "count": 7
      }
}
Set max value and change number of ticks for 811 and 812
   "y": {
      "padding": {"top": 0, "bottom": 0},
      "max": 40000,
      "tick": {
        "format": "dollar",
        "count": 5
      }
    },
#Set max value and change number of ticks for 821 and 822
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 50000,
  "tick": {
    "format": "dollar",
    "count": 6
  }
},

**Figure 3-19 Made hand corrections to x axis ticks.**

For normal line charts handled in the college-affordability.urban.org repo at:
`college-affordability.urban.org/components/30-components/graphs/graph/graph.jsx`
in various blocks specific to line and area charts. Given that this chart is a single edge case (toggle line chart), made corrections by hand, namely:
- set `x.tick.count: 14`
- added empty tick `""` to start and end of x.categories array
- added empty tick `null` to start and end of each data series array in `data.sets`

#Figure 3-22:
#First set of multiples- need to add "groups": [["Tuition and fees covered by grant aid", "Remaining (net) tuition and fees", "Living expenses covered by grant aid", "Remaining (net) living expenses"]]
#First set of multiples set max y value and ticks:
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 30000,
  "tick": {
    "format": "dollar",
    "count": 4
  }
},
#Second set of multiples- need to add "groups": [["Tuition and fees covered by grant aid", "Remaining (net) tuition and fees", "Living expenses covered by grant aid", "Remaining (net) living expenses"]]
  Also set max y value in first graph: "y": {"padding": {"top": 0, "bottom": 0}, "max": 70000,

#Third set of multiples- set max y value and number of ticks
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 20000,
  "tick": {
    "format": "dollar",
    "count": 5
  }
},
#Fourth set of multiples- need to add "groups": [["Tuition and fees covered by grant aid", "Remaining (net) tuition and fees", "Living expenses covered by grant aid", "Remaining (net) living expenses"]]
#need to set max y-value and ticks
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 40000,
  "tick": {
    "count": 5,
    "format": "dollar"
  }
},


#SECTION 4: FINANCIAL AID

#Figure 4-7 (all multiples)
#set max y value and ticks
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 20000,
  "tick": {
    "format": "dollar",
    "count": 5
  }
}
#insert space to x-values after Indepedent or Dependent so that x-values are two lines total

**Figure 4-8 had to manually change the ordering of the sets and had to replace "groups" aray with:**
```
	"groups": [
	[
	"Federal",
	"State",
	"Veterans",
	"Institutional",
	"Private"
	]
```
#Figure 4-9
for graphs 1-3, change number of ticks
"y": {
  "max": 8000,
  "padding": {"top": 0, "bottom": 0},
  "tick": {
    "format": "$s",
    "count": 5
  }
},

for graphs 11-33, change number of ticks
"y": {
  "max": 6000,
  "padding": {"top": 0, "bottom": 0},
  "tick": {
    "format": "$s",
    "count": 4
  }
},

**Figure 4-19: had to manually change groups array to:**
```
	"groups": [
	  [
	    "Institutional grant aid per full-time student", 
	    "Remaining (net) tuition and fees per full-time student",
	    "Institutional grant aid per recipient", 
	    "Remaining (net) tuition and fees per recipient"
	    ]
	 ]
```

**Figure 4-20 : 
1) had to manually change group array to:**
```
	"groups": ["Need-based", "Non-need-based"]
```

**Figure 4-21 : 
add brackets to single x-categories in 4-211 and 4-212
change y tick values
"y": {
  "padding": {"top": 0, "bottom": 0},
  "max": 1000,
  "tick": {
    "format": "dollar",
    "count": 3
  }

2) had to manually change order of sets


**Figure 4-24 : change y tick values
 "y": {
      "padding": {"top":0, "bottom": 0},
       "max": 25,
      "tick": {
        "format": "dollar",
        "count": 6
      }

**Figure 4-21 : make x label two lines, in first two graphs of multiple, in order to widen the graph



#SECTION 5: COVERING EXPENSES

Figure 5-1 (all multiples)
1) in first graph, add bracket for x.categories since single category "All families"
2) set max y value and ticks
    "y": {
      "padding": {"top": 0, "bottom": 0},
      "max": 100000,
      "tick": {
        "count": 3,
        "format": "dollar"
      }
    },

Figure 5-13: 
1) in first graph, add bracket for x.categories since single category "All Undergraduates"
2) in first, add space to x-axis labels for two lines so "All Under-                 graduates" 
3) in the third graph, add space to x-axis labels for two lines  so  "Less than          ....." or "$30,000–            ........." for instance
4) in the fourth graph, add space to x-axis labels for two lines so "Full-time           ....."

Figure 5-17
1) in the first graph, make x-label three lines by adding spaces in between "All full-time/ dependent/ students"
2) in the second graph, make each x-label two lines, so  "Less than          ....." or "$30,000–            ........." for instance
3) set max y-value and ticks

    "y": {
      "padding": {"top": 0, "bottom": 0},
      "tick": {
        "count": 3,
        "format": "dollar"
      },
      "max": 20000
    },
#SECTION 6: AFTER COLLEGE

#Figure 6-8
add bracket to "categories": ["Education Debt"]

#Figure 6-20
make x-labels two lines after dash by adding space: $1,000– / $5,000

#SECTION 7: STUDENT PROFILES


#Figure 7-3 had to tweak groups array:
"groups": [
  [
    "Expected family contribution", 
    "Federal grants", 
    "Military/Veterans", 
    "State grants", 
    "Institutional grants", 
    "Private and employer aid", 
    "Federal student loans", 
    "Federal  parent loans", 
    "Private loans", 
    "Earnings and other resources", 
    "Tuition and fees", 
    "NonTF budget"
    ]
  ]

#manually set colors to avoid duplicates
"colors": {
  "Institutional grants":"#1696d2",
  "Military\/Veterans": "#000000",
  "Tuition and fees": "#55b748",
  "Earnings and other resources": "#ffff00",
  "Private and employer aid": "#d2d2d2",
  "NonTF budget": "#ec008b",
  "Federal grants": "#6100ec",
  "State grants": "#d700ec",
  "Private loans": "#88ec00",
  "Federal student loans": "#ffa500",
  "Expected family contribution": "#ec0015",
  "Federal  parent loans": "#00ecd7"
},


#Figure 7-7 #had to change groups array:

	"groups": [
	  [
	    "Private loans", 
	    "Institutional grants", 
	    "Tuition and fees", 
	    "State public grants",
	    "Federal grants", 
	    "NonTF budget", 
	    "EFC", 
	    "Military/Veterans", 
	    "Private and employer aid", 
	    "Federal parent loans", 
	    "Federal student loans", 
	    "Earnings and other resources"
	    ]
	  ],

#Figure 7-11 need to change groups array to:
"groups": [
  [
    "Expected family contribution", 
    "Federal grants", 
    "Military/Veterans", 
    "State grants", 
    "Institutional grants", 
    "Private and employer aid", 
    "Federal student loans", 
    "Federal  parent loans", 
    "Private loans", 
    "Earnings and other resources",
    "Budget beyond tuition and fees", 
    "Tuition and fees"
    ]
  ],
#need to set colors manually to avoid duplicates
"colors": {
  "Expected family contribution":"#d700ec",
  "Federal grants":"#000000",
  "Military/Veterans":"#55b748",
  "State grants": "#00ecd7",
  "Institutional grants":"#1696d2",
  "Private and employer aid":"#88ec00",
  "Federal student loans": "#d2d2d2",
  "Federal  parent loans":"#6100ec",
  "Private loans": "#ec008b",
  "Earnings and other resources":"#ffa500",
  "Budget beyond tuition and fees":"#ec0015",
  "Tuition and fees":"#ffff00"
},

 #Figure 7-15 need to change groups array to:
"groups": [
  [
    "Expected family contribution", 
    "Federal grants", 
    "Military/Veterans", 
    "State grants", 
    "Institutional grants", 
    "Private and employer aid", 
    "Federal student loans", 
    "Federal  parent loans", 
    "Private loans", 
    "Earnings and other resources",
    "Budget beyond tuition and fees", 
    "Tuition and fees"
    ]
  ],
#need to change colors to avoid duplicates
"colors": {
  "Expected family contribution":"#d700ec",
  "Federal grants":"#000000",
  "Military/Veterans":"#55b748",
  "State grants":"#00ecd7",
  "Institutional grants":"#ffff00",
  "Private and employer aid":"#88ec00",
  "Federal student loans":"#d2d2d2",
  "Federal  parent loans":"#6100ec",
  "Private loans":"#ec0015",
  "Earnings and other resources":"#ffa500",
  "Budget beyond tuition and fees":"#ec008b",
  "Tuition and fees": "#1696d2"
},
#Figure 7-19 need to change groups array
"groups": [
  [
    "Expected family contribution", 
    "Federal grants", 
    "Military/Veterans", 
    "State grants", 
    "Institutional grants", 
    "Private and employer aid", 
    "Federal student loans", 
    "Federal  parent loans", 
    "Private loans", 
    "Budget beyond tuition and fees", 
    "Tuition and fees"
    ]
  ],
#need to set colors to avoid duplicates
"colors": {
  "Expected family contribution":"#d700ec",
  "Federal grants": "#000000",
  "Military/Veterans": "#55b748",
  "State grants": "#ffff00",
  "Institutional grants": "#1696d2",
  "Private and employer aid": "#ec008b", 
  "Federal student loans": "#d2d2d2",
  "Federal  parent loans": "#6100ec", 
  "Private loans": "#88ec00",
  "Budget beyond tuition and fees": "#ec0015",
  "Tuition and fees": "#00ecd7"
},


The following json shows the move slots every wrestler has, as well as the opponent state, setup, and button combinations:

```json

{
  "Grappling": {
    "Front Grapple": {
      "Front Weak Grapple (Tap A)": {
        "Opponent State": "Standing Facing Player",
        "Setup": "Tap A in Front of Standing Opponent",
        "Moves": {
          "A": "Front Weak Grapple 1",
          "←/→ + A": "Front Weak Grapple 2",
          "↑ + A": "Front Weak Grapple 3",
          "↓ + A": "Front Weak Grapple 4",
          "B": "Front Weak Grapple 5",
          "←/→ + B": "Front Weak Grapple 6",
          "↑ + B": "Front Weak Grapple 7",
          "↓ + B": "Front Weak Grapple 8"
        }
      },
      "Front Strong Grapple (Hold A)": {
        "Opponent State": "Standing Facing Player",
        "Setup": "Hold A in Front of Standing Opponent",
        "Moves": {
          "A": "Front Strong Grapple 1",
          "←/→ + A": "Front Strong Grapple 2",
          "↑ + A": "Front Strong Grapple 3",
          "↓ + A": "Front Strong Grapple 4",
          "B": "Front Strong Grapple 5",
          "←/→ + B": "Front Strong Grapple 6",
          "↑ + B": "Front Strong Grapple 7",
          "↓ + B": "Front Strong Grapple 8",
          "Control Stick": "Front Finisher"
        }
      }
    },
    "Back Grapple": {
      "Back Weak Grapple (Tap A)": {
        "Opponent State": "Standing facing away",
        "Setup": "Tap A when behind a standing opponent",
        "Moves": {
          "A": "Back Weak Grapple 1",
          "←/→/↑/↓ + A": "Back Weak Grapple 2",
          "B": "Back Weak Grapple 3",
          "←/→/↑/↓ + B": "Back Weak Grapple 4"
        }
      },
      "Back Strong Grapple (Hold A)": {
        "Opponent State": "Standing facing away",
        "Setup": "Hold A when behind a standing opponent",
        "Moves": {
          "A": "Back Strong Grapple 1",
          "←/→/↑/↓ + A": "Back Strong Grapple 2",
          "B": "Back Strong Grapple 3",
          "←/→/↑/↓ + B": "Back Strong Grapple 4",
          "Control Stick": "Back Finisher"
        }
      }
    },
    "Reversals": {
      "Opponent State": "Initiating a Grapple",
      "Setup": "",
      "Moves": [
        "Back Weak Grapple Counter",
        "Back Strong Grapple Counter"
      ]
    }
  },
  "Standing": {
    "Weak Striking": {
      "Arm Striking": {
        "Opponent State": [
          "Standing facing player",
          "Standing facing away"
        ],
        "Setup": "Standing Close to Opponent",
        "Moves": {
          "(Tap) B": "Weak Arm Strike 1",
          "←/→/↑/↓ + (Tap) B": "Weak Arm Strike 2"
        }
      },
      "Leg Striking": {
        "Opponent State": [
          "Standing facing player",
          "Standing facing away"
        ],
        "Setup": "Standing Less-Close to Opponent",
        "Moves": {
          "(Tap) B": "Weak Leg Strike 1",
          "←/→/↑/↓ + (Tap) B": "Weak Leg Strike 2"
        }
      }
    },
    "Strong Striking (Hold B)": {
      "Opponent State": [
        "Standing facing player",
        "Standing facing away"
      ],
      "Setup": "Stand Near Opponent",
      "Moves": {
        "(Hold) B": "Strong Strike 1",
        "←/→/↑/↓ + (Hold) B": "Strong Strike 2",
        "A + B": "Strong Strike 3"
      }
    },
    "Recovering (Hold R When Getting Up)": {
      "Opponent State": [
        "Standing facing player",
        "Standing facing away"
      ],
      "Setup": "Hold R When Getting Up",
      "Moves": {
        "B": "Ducking Attack"
      }
    },
    "Counter Attack (Strike Counters)": {
      "Counter Punch": {
        "Opponent State": "Throwing a Punch",
        "Setup": "Timing the button press exactly",
        "Moves": {
          "R": "Counter Punch",
          "R (with Special)": "Special Counter Punch"
        }
      },
      "Counter Kick": {
        "Opponent State": "",
        "Setup": "",
        "Moves": {
          "A": "Counter Kick 1",
          "B": "Counter Kick 2"
        }
      }
    },
    "Walking": {
      "Opponent State": "Any",
      "Setup": "n/a",
      "Moves": {
        "←/→/↑/↓": "Walking Style"
      }
    },
    "Running (C-Down)": {
      "Running Attack (Strike)": {
        "Opponent State": "Standing",
        "Setup": "Press C-Down to run, then press attack buttons",
        "Moves": {
          "Run + B": "Weak Running Attack 1",
          "Run + A + B": "Weak Running Attack 2",
          "←/→/↑/↓ + Run + B": "Strong Running Attack 1",
          "←/→/↑/↓ + Run + A + B": "Strong Running Attack 2"
        }
      },
      "Running Grapple": {
        "Opponent State": "Standing",
        "Setup": "Press C-Down to run, then press A when close",
        "Moves": {
          "Run + A (To Front of Opponent)": "Running Front Grapple",
          "Run + A (To Back of Opponent)": "Running Back Grapple"
        }
      },
      "Running Ground Attack (Strike)": {
        "Opponent State": "On Mat (Facing Up, Down, or Sitting)",
        "Setup": "Press C-Down to run, then press B when near downed opponent",
        "Moves": {
          "Run + B (To Opponent Facing Up)": "Facing-Up Running Ground Attack",
          "Run + B (To Opponent Facing Down)": "Facing-Down Running Ground Attack",
          "Run + B (To Opponent Sitting Up)": "Sitting-Up Running Ground Attack",
          "Run + B (To Opponent Sitting Down)": "Sitting-Down Running Ground Attack"
        }
      },
      "Evasion": {
        "Opponent State": "Any",
        "Setup": "Press C-Down to run, then press R",
        "Moves": {
          "Run + R": "Evading Move"
        }
      }
    }
  },
  "Ground": {
    "Upper Body Submission": {
      "Opponent States": {
        "Facing Up": "Laying flat on their back",
        "Facing Down": "Laying flat on their stomach",
        "Sitting Up": "Sitting with legs straight out in front of them",
        "Sitting Down": "Kneeling on all fours"
      },
      "Setup": "Stand near opponent's head and press A",
      "Moves": {
        "A (Facing Up)": "Facing-Up Upper Body Submission",
        "A (Facing Down)": "Facing-Down Upper Body Submission",
        "A (Sitting Up)": "Sitting-Up Upper Body Submission",
        "A (Sitting Down)": "Sitting-Down Upper Body Submission",
        "A (Special - Facing Up)": "Facing-Up Upper Body Finisher",
        "A (Special - Facing Down)": "Facing-Down Upper Body Finisher"
      }
    },
    "Lower Body Submission": {
      "Opponent States": {
        "Facing Up": "Laying flat on back",
        "Facing Down": "Laying flat on stomach"
      },
      "Setup": "Stand near opponent's feet and press A",
      "Moves": {
        "A (To Opponent Facing Up)": "Facing-Up Lower Body Submission",
        "A (To Opponent Facing Down)": "Facing-Down Lower Body Submission",
        "A (With Special - To Opponent Facing Up)": "Facing-Up Lower Body Finisher",
        "A (With Special - To Opponent Facing Down)": "Facing-Down Lower Body Finisher"
      }
    },
    "Ground Attack (Strike)": {
      "Opponent States": {
        "Facing Up": "Laying flat on back",
        "Facing Down": "Laying flat on stomach",
        "Sitting Up": "Sitting with legs straight out",
        "Sitting Down": "Kneeling on all fours"
      },
      "Setup": "Stand near any part of the opponent and press B",
      "Moves": {
        "B (To Opponent Facing Up)": "Facing-Up Ground Attack",
        "B (To Opponent Facing Down)": "Facing-Down Ground Attack",
        "B (To Opponent Sitting Up)": "Sitting-Up Ground Attack",
        "B (To Opponent Sitting Down)": "Sitting-Down Ground Attack"
      }
    }
  },
  "Turnbuckle": {
    "Turnbuckle Attack": {
      "Opponent State": "Standing in corner with back to turnbuckle",
      "Setup": "Stand in front of opponent",
      "Moves": {
        "B": "Turnbuckle Attack 1",
        "←/→/↑/↓ + B": "Turnbuckle Attack 2",
        "Run + B": "Running Turnbuckle Attack 1",
        "Run + A + B": "Running Turnbuckle Attack 2"
      }
    },
    "Corner Counter": {
      "Opponent State": "Standing/Running after Irish-whipping player towards turnbuckle",
      "Setup": "While being Irish-whipped into turnbuckle",
      "Moves": {
        "Rapidly Tapping A/B/L/R": "Irish Whip to Corner-Counter"
      }
    },
    "Tree-of-Woe Attack": {
      "Opponent State": "Hanging upside down in 'tree-of-woe' position",
      "Setup": "Irish-whipping an opponent into the corner, initiating a grapple (weak or strong), and pressing the L Button",
      "Moves": {
        "B": "Tree-of-Woe Attack 1",
        "←/→/↑/↓ + B": "Tree-of-Woe Attack 2",
        "Run + B": "Running Tree-of-Woe Attack"
      }
    },
    "Front Turnbuckle Grapple": {
      "Front Turnbuckle Weak Grapple (Tap A)": {
        "Opponent State": "Standing in corner with back to turnbuckle",
        "Setup": "Initiate weak grapple to opponent in corner",
        "Moves": {
          "A": "Front Turnbuckle Weak Grapple 1",
          "B": "Front Turnbuckle Weak Grapple 2"
        }
      },
      "Front Turnbuckle Strong Grapple (Hold A)": {
        "Opponent State": "Standing in corner with back to turnbuckle",
        "Setup": "Initiate strong grapple to opponent in corner",
        "Moves": {
          "A": "Front Turnbuckle Strong Grapple 1",
          "B": "Front Turnbuckle Strong Grapple 2",
          "Control Stick (With Special)": "Front Turnbuckle Finisher"
        }
      }
    },
    "Back Turnbuckle Grapple": {
      "Back Turnbuckle Weak Grapple": {
        "Opponent State": "Standing in corner facing turnbuckle",
        "Setup": "Initiate weak grapple (Tap A) to opponent in corner and press C-Left to turn them around, then A to back-grapple",
        "Moves": {
          "A": "Back Turnbuckle Weak Grapple 1",
          "B": "Back Turnbuckle Weak Grapple 2"
        }
      },
      "Back Turnbuckle Strong Grapple": {
        "Opponent State": "Standing in corner facing turnbuckle",
        "Setup": "Initiate strong grapple (Hold A) to opponent in corner and press C-Left to turn them around, then A to back-grapple",
        "Moves": {
          "A": "Back Turnbuckle Strong Grapple 1",
          "B": "Back Turnbuckle Strong Grapple 2",
          "Control Stick (With Special)": "Back Turnbuckle Finisher"
        }
      }
    },
    "Counter Grapple (to Flying-Attack)": {
      "Opponent State": "On Top Rope (Facing Player or Away)",
      "Setup": "Press A as opponent prepares to fly",
      "Moves": {
        "A (Opponent Facing Player)": "Front Flying Counter Grapple",
        "A (Opponent Facing Away)": "Back Flying Counter Grapple"
		}
    },
	"Flying Attack": {
	      "Standing Opponent Flying Attack": {
	        "Opponent State": "Standing in Ring",
	        "Setup": "D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
	        "Moves": "Standing Opponent Flying Attack"
			},
			"Standing Opponent Flying Attack to Outside": {
				"Opponent State": "Standing Outside of Ring",
		        "Setup": "D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
				"Moves": "Standing Opponent Flying Attack to Outside"
			},
			"Standing Opponent Flying Finisher": {
				"Opponent State": "Standing In or Outside of Ring",
		        "Setup": "With Special, D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
				"Moves": "Standing Opponent Flying Finisher"
			},
			"Laying Opponent Flying Attack": {
				"Opponent State": "Laying Down In Ring",
		        "Setup": "D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
				"Moves": "Laying Opponent Flying Attack"
			},
			"Laying Opponent Flying Attack to Outside": {
				"Opponent State": "Laying Down Outside of Ring",
		        "Setup": "D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
				"Moves": "Laying Opponent Flying Attack to Outside"
	      },
	      "Laying Opponent Flying Finisher": {
				"Opponent State": "Laying Down In or Outside of Ring",
		        "Setup": "With Special, D-Pad plus run (C-Down) into turnbuckle, release D-Down to jump off",
				"Moves": "Laying Opponent Flying Finisher"
			},
			"Turnbuckle Inside Attack (Bret's Rope Attack)": {
				"Opponent State": "Laying Down Inside Ring Near Corner",
				"Setup": "In corner press D-Pad torwards corner while pressing A",
				"Moves": {
					"A": "Attack from Second Rope"
				}
			}
		},
		"Corner Taunt": {
			"Opponent State": "Any",
			"Setup": "Stand in corner pressing D-Pad towards turnbuckle plus Control Stick",
			"Moves": {
				"Control Stick": "Corner Taunt"
			}
		},
		"Turnbuckle Taunt": {
			"Opponent State": "Any",
			"Setup": "From top turnbuckle, before releasing C-Down, taunt with Control Stick",
			"Moves": "Control Stick": "Top Turnbuckle Taunt"
		}
	},
	"Ringside": {
		"Grapple to Apron": {
			"Opponent State": "Standing on Apron",
			"Setup": "From inside ring, initiate weak or strong grapple to opponent standing on apron",
			"Moves": {
			"A or B": "Weak Grapple to Apron",
			"A or B": "Strong Grapple to Apron",
			"Control Stick": "Special Grapple to Apron"
			}
		},
		"Counter Grapple from Apron": {
			"Opponent State": "Grappling player in ring from ring apron",
			"Setup": "Being grappled by opponent from apron",
			"Moves": {
				"Rapidly tapping A and B": "Counter Grapple from Apron"
			}
		},
		"Rope Inside Attack": {
			"Opponent State": "Laying on mat",
			"Setup": "Standing between downed opponent and ring ropes",
			"Moves": {
				"D-Pad + A": "Rope Inside Attack"
			}
		},
		"Flying Attack to Outside": {
			"Flying Attack": {
				"Opponent State": "Outside of ring",
				"Setup": "Standing inside ring up against ring ropes",
				"Moves": {
					"D-Pad + A": "Flying Attack"
				}
			},
			"Running Diving Attack": {
				"Opponent State": "Outside of ring",
				"Setup": "Inside ring running torwards ring ropes",
				"Moves": {
					"A": "Running Diving Attack 1",
					"D-Pad + A": "Running Diving Attack 2"
				}
			}
		},
		"Running Diving Taunt": {
			"Opponent State": "Outside of ring",
			"Setup": "Inside ring running torwards ring ropes",
			"Moves": {
				"Control Stick": "Running Diving Taunt"
			}
		},
		"Rebound Flying Attack": {
			"Opponent State": "Standing",
			"Setup": "Inside ring running torwards ring ropes",
			"Moves": {
				"A": "Rebound Flying Attack"
			}
		}
	},
	"Apron": {
		"Apron Attack": {
			"Apron Strike to Inside": {
				"Opponent State": "Standing inside of ring",
				"Setup": "Standing on ring apron",
				"Moves": {
					"B": "Apron Strike to Inside"
				}
			},
			"Apron Strike to Outside": {
				"Opponent State": "Standing outside of ring",
				"Setup": "Standing on ring apron",
				"Moves": {
					"B": "Apron Strike to Outside"
				}
			},
		},
		"Grapple From Apron": {
			"Opponent State": "Standing inside ring near ropes",
			"Setup": "Initiate weak or strong grapple to opponent in ring while standing on ring apron",
			"Moves": {
				"A or B": "Weak Grapple from Apron",
				"A or B": "Strong Grapple from Apron",
				"Control Stick": "Finisher from Apron"
			}
		},
		"Counter Grapple from Apron": {
			"Opponent State": "Grapping player on ring apron while Standing inside ring",
			"Setup": "Being grappled by opponent while standing on ring apron",
			"Moves": {
				"Rapidly Tapping A and B": "Counter Grapple from Apron"
			}
		},		
		"Flying Attack from Apron": {
			"Flying Attack": {
				"Opponent State": "Outside of ring",
				"Setup": "Standing on ring apron",
				"Moves": {
					"D-Pad + A": "Flying Attack"
				}
			},
			"Running Flying Attack": {
				"Opponent State": "Outside of ring",
				"Setup": "Running on ring apron",
				"Moves": {
					"A": "Running Flying Attack"
				}
			},
		},
		"Flying Attack to Ring": {
			"Opponent State": "Inside Ring",
			"Setup": "Standing on Ring Apron",
			"Moves": {
				"A": "Flying Attack (Standing Opponent)",
				"A": "Flying Attack (Laying Opponent)",
				"A": "Flying Attack (Special)"
			}
		},
		"Apron Taunt": {
			"Opponent State": "Any",
			"Setup": "Standing on ring apron",
			"Moves": {
				"Control Stick": "Apron Taunt"
			}
		}
	},
	"Irish Whip": {
		"Irish Whip Attack (Strike)": {
			"Opponent State": "Running Torwards Opponent",
			"Setup": "Standing",
			"Moves": {
				"B": "Irish Whip Attack"
			}
		},
		"Irish Whip Grapple": {
			"Irish Whip Grapple (Weak)": {
				"Opponent State": "Irish-whipped from weak grapple, running torwards player",
				"Setup": "Standing, opponent running torwards player",
				"Moves": {
					"Tap A": "Weak Irish-Whip Grapple 1",
					"Hold A": "Weak Irish-Whip Grapple 2"
				}
			},
			"Irish Whip Grapple (Strong)": {
				"Opponent State": "Irish-whipped from strong grapple, running torwards player",
				"Setup": "Standing, opponent running torwards player",
				"Moves": {
					"Tap A": "Strong Irish-Whip Grapple 1",
					"Hold A": "Strong Irish-Whip Grapple 2",
					"Control Stick": "Irish-Whip Finisher"
				}
			}
		},
	"Taunt": {
		"Taunt": {
			"Opponent State": "Any",
			"Setup": "Standing",
			"Moves": {
				"Control Stick Up": "Standing Taunt 1",
				"Conrtol Stick Left": "Standing Taunt 2",
				"Control Stick Right": "Standing Taunt 3"
			}
		},
		"Special Taunt": {
			"Opponent State": "Any",
			"Setup": "Standing, has special",
			"Moves": {
				"Control Stick": "Special Taunt"		
		},
		"Ducking Taunt": {
			"Opponent State": "Any",
			"Setup": "Standing or ducking",
			"Moves": {
				"Control Stick Down": "Ducking Taunt"
			}
		},
		"Celebration Taunt": {
			"Opponent State": "Defeated, match over",
			"Setup": "Win match",
			"Moves": "Celebration Taunt"
		},
		"Entry Way Taunt": {
			"Opponent State": "n/a",
			"Setup": "Player's character making way to ring",
			"Moves": "Entry Way Taunt"		
		}
	},
	"Double-Team": {
		"Double-Team Grapple": {
			"Standing Double Team Grapple": {
				"Opponent State": "Standing",
				"Setup": "Player and another character grapple opponent at same time from front, back, or sandwich position",
				"Moves": {
					"A": ["Front Double-Team Grapple", "Back Double-Team Grapple", "Sandwich Double-Team Grapple"]
				}
			},
			"Running Double-Team Grapple": {
				"Opponent State": "Running torwards player and another opponent",
				"Setup": "Standing",
				"Moves": {
					"A": "Running Double-Team Grapple"
				}
			}
		},
		"Double Team Flying Attack": {
			"Opponent State": "Held up on the shoulders of an opponent",
			"Setup": "To hold opponent up on shoulders, grapple and C-Up.  When Opponent on shoulders of other player, execute top-rope Flying Attack or Flying Attack from Apron",
			"Moves": ["From Top Rope Into Ring", "From Top Rope Outside", "From Apron"]
		}
	}
}

```

## Available Moves for Each Wrestler
### Front Weak Grapple 1-4

| Move                  | Power | KO    | Bleed | Feature |
| --------------------- | ----- | ----- | ----- | ------- |
| Arm Drag              | F     | FALSE | FALSE |         |
| Chop 01               | F     | FALSE | FALSE |         |
| Chop 02               | F     | FALSE | FALSE |         |
| Chop 03               | F     | FALSE | TRUE  |         |
| Chop 04               | F     | FALSE | FALSE |         |
| Club to Neck          | F     | FALSE | FALSE |         |
| Double Axe Handle     | F     | FALSE | FALSE |         |
| Double Leg Takedown   | F     | FALSE | FALSE |         |
| Elbow Strike          | F     | FALSE | FALSE |         |
| Elbow to Back of Head | F     | FALSE | FALSE |         |
| European Uppercut     | F     | FALSE | FALSE |         |
| Eye Rake              | F     | FALSE | FALSE |         |
| Fireman Carry         | F     | FALSE | FALSE |         |
| Head Butt 01          | F     | FALSE | TRUE  |         |
| Head Butt 02          | F     | FALSE | TRUE  |         |
| Head Butt 03          | F     | FALSE | TRUE  |         |
| Headlock and Punch    | F     | FALSE | FALSE |         |
| Headlock and Thrust   | F     | FALSE | FALSE |         |
| Jumping Front Kick    | F     | FALSE | FALSE |         |
| Knee Lift             | F     | FALSE | FALSE |         |
| Knee Strike           | F     | FALSE | FALSE |         |
| Knee Sweep            | F     | FALSE | FALSE |         |
| Mini Shin Kicks       | F     | FALSE | FALSE |         |
| Overhand Punch        | F     | FALSE | FALSE |         |
| One Hand Scoop Slam   | F     | FALSE | FALSE |         |
| Scoop Slam            | E     | FALSE | FALSE |         |
| Slap                  | F     | FALSE | FALSE |         |
| Snapmare              | F     | FALSE | FALSE |         |
| Throat Thrust         | F     | FALSE | FALSE |         |
| Underhand Hook Punch  | F     | FALSE | FALSE |         |

### Front Weak Grapple 5-8

| Move                      | Power | KO    | Bleed | Feature |
| ------------------------- | ----- | ----- | ----- | ------- |
| Arm Dragon Screw          | E     | FALSE | FALSE | null    |
| Arm Wrench/Elbow Smash    | E     | FALSE | FALSE | null    |
| Arm Wrench with Hook Kick | E     | FALSE | FALSE | null    |
| Back Body Flip            | E     | FALSE | FALSE | null    |
| Chop Down                 | E     | FALSE | FALSE | null    |
| Drop Suplex 01            | E     | FALSE | FALSE | null    |
| Drop Suplex 02            | E     | FALSE | FALSE | null    |
| Double Underhook Suplex   | E     | FALSE | FALSE | null    |
| Fallaway Slam             | E     | FALSE | FALSE | null    |
| Falling Neck Breaker      | E     | FALSE | FALSE | null    |
| Falling Powerslam         | E     | FALSE | FALSE | null    |
| Falling Suplex            | D     | FALSE | FALSE | null    |
| Gordbuster 01             | E     | FALSE | FALSE | null    |
| Gordbuster 02             | D     | FALSE | FALSE | null    |
| Headlock Takedown         | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 01  | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 02  | E     | FALSE | FALSE | null    |
| Hip Throw                 | E     | FALSE | FALSE | null    |
| Hip Toss                  | E     | FALSE | FALSE | null    |
| Jawbreaker                | F     | FALSE | FALSE | null    |
| Knee Strikes 01           | F     | FALSE | FALSE | null    |
| Knee Strikes 02           | F     | FALSE | FALSE | null    |
| Knee Strikes 03           | E     | FALSE | FALSE | null    |
| Mini Chops                | E     | FALSE | FALSE | null    |
| Neck Breaker 01           | E     | FALSE | FALSE | null    |
| Neck Breaker 02           | E     | FALSE | FALSE | null    |
| Piledriver 01             | D     | FALSE | FALSE | null    |
| Piledriver 02             | E     | FALSE | FALSE | null    |
| Piledriver 03             | D     | FALSE | FALSE | null    |
| Piledriver 04             | D     | FALSE | FALSE | null    |
| Rib Breaker               | E     | FALSE | FALSE | null    |
| Russian Leg Sweep         | E     | FALSE | FALSE | null    |
| Shoulder Breaker          | E     | FALSE | FALSE | null    |
| Shoulder Thrusts          | E     | FALSE | FALSE | null    |
| Snap Suplex               | E     | FALSE | FALSE | null    |
| Stall Suplex              | E     | FALSE | FALSE | null    |
| Suplex                    | E     | FALSE | FALSE | null    |
| Tie Up Knee Strikes       | F     | FALSE | FALSE | null    |
| Underhook Suplex/Knee     | D     | FALSE | FALSE | null    |
### Front Strong Grapple 1-8

| Move                               | Power | KO    | Bleed | Feature |
| ---------------------------------- | ----- | ----- | ----- | ------- |
| Bearhug                            | E     | FALSE | FALSE | Submit  |
| Backslide Pin                      | C     | FALSE | FALSE | Pin     |
| Belly to Back Flip Suplex          | C     | TRUE  | FALSE | null    |
| Belly to Back Spin Suplex          | C     | FALSE | FALSE | null    |
| Belly to Back Suplex               | C     | FALSE | FALSE | null    |
| Belly to Belly Suplex 01           | C     | FALSE | FALSE | null    |
| Belly to Belly Suplex 02           | C     | FALSE | FALSE | null    |
| Body Press Drop                    | D     | FALSE | FALSE | null    |
| Body Press to Front Slam           | C     | FALSE | FALSE | null    |
| Brainbuster                        | B     | FALSE | FALSE | null    |
| Canadian Back Breaker              | E     | FALSE | FALSE | Submit  |
| Capture Suplex                     | B     | FALSE | FALSE | null    |
| Chicken Wing Suplex Pin            | C     | FALSE | FALSE | null    |
| Chokeslam from Hell                | C     | FALSE | FALSE | null    |
| Chokeslam 01                       | C     | FALSE | FALSE | null    |
| Chokeslam 02                       | C     | FALSE | FALSE | null    |
| Choke Takedown                     | D     | FALSE | FALSE | null    |
| Climb Up Wheel Kick                | D     | FALSE | FALSE | null    |
| Clinching Slam                     | C     | FALSE | FALSE | null    |
| DDT 01                             | C     | FALSE | FALSE | null    |
| DDT 02                             | C     | FALSE | FALSE | null    |
| DDT 03                             | D     | FALSE | FALSE | null    |
| Death Valley Driver                | C     | FALSE | FALSE | null    |
| Double Arm DDT                     | C     | FALSE | FALSE | null    |
| Double Chokelift Slam              | C     | FALSE | FALSE | null    |
| Dragon Screw 01                    | E     | FALSE | FALSE | null    |
| Dragon Screw 02                    | E     | FALSE | FALSE | null    |
| Falcon Arrow                       | C     | FALSE | FALSE | null    |
| Fallaway Slam                      | D     | FALSE | FALSE | null    |
| Falling Hip Toss                   | C     | FALSE | FALSE | null    |
| Falling Nexk Breaker               | D     | FALSE | FALSE | null    |
| Fireman Carry to Pancake           | D     | FALSE | FALSE | null    |
| Fire Thunder Driver                | C     | FALSE | FALSE | null    |
| Fisherman DDT                      | C     | FALSE | FALSE | null    |
| Fisherman Suplex                   | C     | FALSE | FALSE | null    |
| Front Face Pancake                 | C     | FALSE | FALSE | null    |
| Front Powerslam                    | E     | FALSE | FALSE | null    |
| Giant Headbutt                     | C     | FALSE | FALSE | null    |
| Guillotine Choke                   | F     | FALSE | FALSE | null    |
| Headlock                           | F     | FALSE | FALSE | null    |
| Hopping Rolling Pin                | C     | FALSE | FALSE | null    |
| Hopping Sunset Flip Pin            | C     | FALSE | FALSE | null    |
| Hurracanrana Pin                   | D     | FALSE | FALSE | null    |
| Judo Front Slam                    | E     | FALSE | FALSE | null    |
| Knee Smash                         | C     | FALSE | FALSE | null    |
| Manhattan Drop                     | D     | FALSE | FALSE | null    |
| Michinoku Driver                   | C     | FALSE | FALSE | null    |
| Military Press                     | E     | FALSE | FALSE | null    |
| Northern Lights Suplex 01          | C     | FALSE | FALSE | null    |
| Northern Lights Suplex 02          | E     | FALSE | FALSE | null    |
| Oklahoma Slam                      | B     | FALSE | FALSE | null    |
| Powerbomp Pin 01                   | C     | FALSE | FALSE | null    |
| Powerbomp Pin 02                   | C     | FALSE | FALSE | null    |
| Powerbomp Pin 03                   | B     | FALSE | FALSE | null    |
| Powerbomp Pin 04                   | B     | FALSE | FALSE | null    |
| Powerbomp Pin 05                   | C     | FALSE | FALSE | null    |
| Powerbomp Pin 06                   | B     | FALSE | FALSE | null    |
| Powerbomp Pin 07                   | C     | FALSE | FALSE | null    |
| Powerbomp Pin 08                   | C     | FALSE | FALSE | null    |
| Powerbomp Pin 09                   | C     | FALSE | FALSE | null    |
| Powerslam                          | D     | FALSE | FALSE | null    |
| Reverse Armbar                     | F     | FALSE | FALSE | null    |
| Reverse Suplex                     | D     | FALSE | FALSE | null    |
| Rolling Leg Lock                   | F     | FALSE | FALSE | null    |
| Rope Drop Clothesline              | E     | FALSE | FALSE | null    |
| Running Knee Strike                | E     | FALSE | FALSE | null    |
| Running Powerbomb Pin              | C     | FALSE | FALSE | null    |
| Sambo Suplex                       | C     | FALSE | FALSE | null    |
| Scoop Piledriver                   | D     | FALSE | FALSE | null    |
| Shoulder Breaker Thrust            | E     | FALSE | FALSE | null    |
| Sidewalk Slam                      | D     | FALSE | FALSE | null    |
| Small Package                      | C     | FALSE | FALSE | null    |
| Snap Powerbomb 01                  | C     | FALSE | FALSE | null    |
| Snap Powerbomb 02                  | C     | FALSE | FALSE | null    |
| Snap Powerbomb 03                  | C     | FALSE | FALSE | null    |
| Somersault Kick                    | F     | FALSE | FALSE | null    |
| Spinning Leg Takedown              | C     | FALSE | FALSE | null    |
| Standing Armbar                    | F     | FALSE | FALSE | Submit  |
| Standing Clothesline               | D     | FALSE | FALSE |         |
| Stalling Brainbuster               | B     | FALSE | FALSE |         |
| Stalling Piledriver                | C     | FALSE | FALSE |         |
| Strong Sambo Suplex                | C     | FALSE | FALSE |         |
| Super Shoulder Breaker             | B     | FALSE | FALSE |         |
| Sweep with Mounted Punching        | F     | FALSE | FALSE | Submit  |
| Tiger Driver                       | D     | FALSE | FALSE |         |
| Tiger Driver with Pin              | C     | FALSE | FALSE | Pin     |
| Tilt A Whirl Piledriver            | D     | FALSE | FALSE |         |
| Trapping Headbutts                 | E     | FALSE | TRUE  | null    |
| Triple Powerbomb Pin               | C     | FALSE | FALSE | Pin     |
| Two Handed Choke Lift              | E     | FALSE | FALSE | Submit  |
| T-Bone Suplex 01                   | D     | FALSE | FALSE | null    |
| T-Bone Suplex 02                   | C     | FALSE | FALSE | null    |
| Underhook Back Breaker             | C     | FALSE | FALSE | null    |
| Underhook Belly to Belly Suplex 01 | C     | FALSE | FALSE | null    |
| Underhook Belly to Belly Suplex 02 | C     | TRUE  | FALSE | null    |
| Arm Dragon Screw                   | F     | FALSE | FALSE | null    |
| Arm Wrench / Elbow Smash           | E     | FALSE | FALSE | null    |
| Arm Wrench with Hook Kick          | E     | FALSE | FALSE | null    |
| Back Body Flip                     | E     | FALSE | FALSE | null    |
| Chop Down                          | E     | FALSE | FALSE | null    |
| Drop Suplex 01                     | E     | FALSE | FALSE | null    |
| Drop Suplex 02                     | E     | FALSE | FALSE | null    |
| Double Underhook Suplex            | E     | FALSE | FALSE | null    |
| Fallaway Slam                      | E     | FALSE | FALSE | null    |
| Falling Neck Breaker               | E     | FALSE | FALSE | null    |
| Falling Powerslam                  | E     | FALSE | FALSE | null    |
| Falling Suplex                     | D     | FALSE | FALSE | null    |
| Gordbuster 01                      | E     | FALSE | FALSE | null    |
| Gordbuster 02                      | D     | FALSE | FALSE | null    |
| Headlock Takedown                  | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 01           | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 02           | E     | FALSE | FALSE | null    |
| Hip Throw                          | E     | FALSE | FALSE | null    |
| Hip Toss                           | E     | FALSE | FALSE | null    |
| Jawbreaker                         | F     | FALSE | FALSE | null    |
| Knee Strikes 01                    | F     | FALSE | FALSE | null    |
| Knee Strikes 02                    | F     | FALSE | FALSE | null    |
| Knee Strikes 03                    | E     | FALSE | FALSE | null    |
| Mini Chops                         | E     | FALSE | FALSE | null    |
| Neck Breaker 01                    | E     | FALSE | FALSE | null    |
| Neck Breaker 02                    | E     | FALSE | FALSE | null    |
| Piledriver 01                      | D     | FALSE | FALSE | null    |
| Piledriver 02                      | E     | FALSE | FALSE | null    |
| Piledriver 03                      | D     | FALSE | FALSE | null    |
| Piledriver 04                      | D     | FALSE | FALSE | null    |
| Rib Breaker                        | E     | FALSE | FALSE | null    |
| Russian Leg Sweep                  | E     | FALSE | FALSE | null    |
| Shoulder Breaker                   | E     | FALSE | FALSE | null    |
| Shoulder Thrusts                   | E     | FALSE | FALSE | null    |
| Snap Suplex                        | E     | FALSE | FALSE | null    |
| Stall Suplex                       | E     | FALSE | FALSE | null    |
| Suplex                             | E     | FALSE | FALSE | null    |
| Tie Up Knee Strikes                | F     | FALSE | FALSE | null    |
| Underhook Suplex / Knee            | D     | FALSE | FALSE | null    |
### Front Finisher

| Move                                       | Power | KO    | Bleed | Feature |
| ------------------------------------------ | ----- | ----- | ----- | ------- |
| Big Swing                                  | F     | FALSE | FALSE | Null    |
| Brainbuster DDT                            | S     | TRUE  | FALSE | Null    |
| Burning Combo                              | S     | FALSE | FALSE | Null    |
| Butterfly Lock                             | F     | FALSE | FALSE | Submit  |
| Censor Kick                                | B     | TRUE  | FALSE | Null    |
| Chicken Wing Jawbreaker                    | B     | TRUE  | FALSE | Null    |
| Continuous Powerbomb / Death Valley Driver | S     | FALSE | FALSE | Null    |
| Cradle DDT                                 | C     | TRUE  | FALSE | Null    |
| Cross DDT                                  | A     | TRUE  | FALSE | Null    |
| Cross Heel Hold                            | E     | FALSE | FALSE | Submit  |
| Dominator                                  | S     | TRUE  | FALSE | Null    |
| Double Dragon Screw 01                     | A     | FALSE | FALSE | Null    |
| Double Dragon Screw 02                     | A     | FALSE | FALSE | Null    |
| Downward Spiral                            | S     | TRUE  | TRUE  | Null    |
| Emerald Fusion                             | S     | TRUE  | FALSE | Null    |
| FameAsser                                  | S     | TRUE  | TRUE  | Null    |
| Figure Four Combo Pin                      | D     | FALSE | FALSE | Pin     |
| Fireball                                   | A     | TRUE  | FALSE | Null    |
| Fire Thunder                               | S     | TRUE  | FALSE | Null    |
| Flipping Armbar                            | F     | FALSE | FALSE | Submit  |
| Flowing DDT                                | A     | TRUE  | FALSE | Null    |
| Front Russian Sweep                        | S     | TRUE  | TRUE  | Null    |
| Hangmans DDT                               | S     | TRUE  | FALSE | Null    |
| Helicopter Pin                             | S     | FALSE | FALSE | Pin     |
| Hip Toss to Submission                     | G     | FALSE | FALSE | Submit  |
| Huge Chokeslam                             | S     | TRUE  | FALSE | Null    |
| Insider Edge                               | S     | TRUE  | FALSE | Null    |
| Inverted DDT                               | B     | TRUE  | FALSE | Null    |
| Iron Claw                                  | A     | FALSE | TRUE  | Submit  |
| Jack Hammer                                | S     | FALSE | FALSE | Pin     |
| Jackknife Powerbomb                        | S     | TRUE  | FALSE | Null    |
| Jericho Powerbomb                          | A     | TRUE  | FALSE | Null    |
| Jump Swinging DDT                          | S     | TRUE  | FALSE | Null    |
| Kicking Combination 01                     | B     | TRUE  | FALSE | Null    |
| Kicking Combination 02                     | S     | TRUE  | FALSE | Null    |
| Kohya-Otoshi                               | S     | FALSE | FALSE | Pin     |
| Last Ride                                  | S     | TRUE  | FALSE | Null    |
| Leg Sweep / Strong Punching                | F     | FALSE | FALSE | Submit  |
| Linda Slap                                 | B     | TRUE  | FALSE | Null    |
| Mac Stunner                                | S     | TRUE  | FALSE | Null    |
| Mandible Claw                              | E     | FALSE | FALSE | Submit  |
| Mu-ken                                     | A     | FALSE | FALSE | Pin     |
| Old Man Flop                               | G     | FALSE | FALSE | Null    |
| Olympic Slam                               | A     | TRUE  | FALSE | Null    |
| Orange Crush Pin                           | S     | FALSE | FALSE | Pin     |
| Pedigree                                   | S     | TRUE  | TRUE  | Null    |
| Poison Mist                                | D     | FALSE | FALSE | Null    |
| Powerbomb Pin with Slide                   | S     | FALSE | FALSE | Pin     |
| Powerbomb to Facebuster                    | S     | TRUE  | FALSE | Null    |
| Power Clothesline                          | S     | TRUE  | FALSE | Null    |
| Punching Combination 01                    | F     | FALSE | FALSE | Null    |
| Punching Combination 02                    | F     | FALSE | FALSE | Null    |
| Punching Combination 03                    | A     | TRUE  | TRUE  | Null    |
| Rikishi Driver                             | S     | TRUE  | TRUE  | Null    |
| Rios Driver                                | A     | TRUE  | TRUE  | Null    |
| Rockbottom                                 | A     | TRUE  | FALSE | Null    |
| Rushing Armbar                             | E     | FALSE | FALSE | Submit  |
| Russian Neck Drop                          | S     | TRUE  | FALSE | Null    |
| Scoop Reverse DDT                          | B     | TRUE  | FALSE | Null    |
| Screwdriver                                | S     | TRUE  | TRUE  | Null    |
| Shake Rattle and Roll                      | S     | TRUE  | TRUE  | Null    |
| Sidewalk Slam with Submission              | G     | FALSE | FALSE | Null    |
| Six Seconds Magic                          | F     | FALSE | FALSE | Submit  |
| Sky High                                   | S     | FALSE | FALSE | Pin     |
| Small Package DDT                          | S     | TRUE  | FALSE | Null    |
| Snowplow                                   | A     | TRUE  | FALSE | Null    |
| Spinning Falcon Arrow                      | S     | FALSE | FALSE | Pin     |
| Spiral Bomb                                | S     | FALSE | FALSE | Pin     |
| Stephanie Slap                             | B     | TRUE  | FALSE | Null    |
| STO 01                                     | S     | TRUE  | FALSE | Null    |
| STO 02                                     | B     | FALSE | FALSE | Null    |
| Stone Cold Stunner                         | S     | TRUE  | FALSE | Null    |
| Striking Combination                       | A     | TRUE  | FALSE | Null    |
| Strong Lariat                              | S     | TRUE  | FALSE | Null    |
| Sumo Attack 01                             | C     | TRUE  | FALSE | Null    |
| Sumo Attack 02                             | B     | FALSE | FALSE | Null    |
| Super Knee Strike                          | A     | TRUE  | FALSE | Null    |
| Super Powerbomb Pin 01                     | A     | FALSE | FALSE | Pin     |
| Super Powerbomb Pin 02                     | S     | FALSE | FALSE | Pin     |
| Super Snap Powerbomb 01                    | S     | TRUE  | FALSE | Null    |
| Super Snap Powerbomb 02                    | S     | TRUE  | FALSE | Null    |
| Sweet Chin Music                           | A     | TRUE  | FALSE | Null    |
| Tazzplex                                   | S     | TRUE  | FALSE | Null    |
| The Morality Check                         | D     | FALSE | FALSE | Null    |
| Tiger Driver                               | S     | FALSE | FALSE | Pin     |
| TKO                                        | S     | TRUE  | FALSE | Null    |
| Tombstone Piledriver                       | S     | TRUE  | TRUE  | Null    |
| Twist of Fate                              | A     | TRUE  | FALSE | Null    |
| Two Handed Chokeslam                       | S     | TRUE  | FALSE | Null    |
| Ultimate Armbar                            | F     | FALSE | FALSE | Submit  |
| X-Factor                                   | S     | TRUE  | TRUE  | Null    |
| 3/4 Turn Neck Breaker                      | S     | TRUE  | FALSE | Null    |
| Bearhug                                    | E     | FALSE | FALSE | Submit  |
| Backslide Pin                              | C     | FALSE | FALSE | Pin     |
| Belly to Back Flip Suplex                  | C     | TRUE  | FALSE | null    |
| Belly to Back Spin Suplex                  | C     | FALSE | FALSE | null    |
| Belly to Back Suplex                       | C     | FALSE | FALSE | null    |
| Belly to Belly Suplex 01                   | C     | FALSE | FALSE | null    |
| Belly to Belly Suplex 02                   | C     | FALSE | FALSE | null    |
| Body Press Drop                            | D     | FALSE | FALSE | null    |
| Body Press to Front Slam                   | C     | FALSE | FALSE | null    |
| Brainbuster                                | B     | FALSE | FALSE | null    |
| Canadian Back Breaker                      | E     | FALSE | FALSE | Submit  |
| Capture Suplex                             | B     | FALSE | FALSE | null    |
| Chicken Wing Suplex Pin                    | C     | FALSE | FALSE | null    |
| Chokeslam from Hell                        | C     | FALSE | FALSE | null    |
| Chokeslam 01                               | C     | FALSE | FALSE | null    |
| Chokeslam 02                               | C     | FALSE | FALSE | null    |
| Choke Takedown                             | D     | FALSE | FALSE | null    |
| Climb Up Wheel Kick                        | D     | FALSE | FALSE | null    |
| Clinching Slam                             | C     | FALSE | FALSE | null    |
| DDT 01                                     | C     | FALSE | FALSE | null    |
| DDT 02                                     | C     | FALSE | FALSE | null    |
| DDT 03                                     | D     | FALSE | FALSE | null    |
| Death Valley Driver                        | C     | FALSE | FALSE | null    |
| Double Arm DDT                             | C     | FALSE | FALSE | null    |
| Double Chokelift Slam                      | C     | FALSE | FALSE | null    |
| Dragon Screw 01                            | E     | FALSE | FALSE | null    |
| Dragon Screw 02                            | E     | FALSE | FALSE | null    |
| Falcon Arrow                               | C     | FALSE | FALSE | null    |
| Fallaway Slam                              | D     | FALSE | FALSE | null    |
| Falling Hip Toss                           | C     | FALSE | FALSE | null    |
| Falling Nexk Breaker                       | D     | FALSE | FALSE | null    |
| Fireman Carry to Pancake                   | D     | FALSE | FALSE | null    |
| Fire Thunder Driver                        | C     | FALSE | FALSE | null    |
| Fisherman DDT                              | C     | FALSE | FALSE | null    |
| Fisherman Suplex                           | C     | FALSE | FALSE | null    |
| Front Face Pancake                         | C     | FALSE | FALSE | null    |
| Front Powerslam                            | E     | FALSE | FALSE | null    |
| Giant Headbutt                             | C     | FALSE | FALSE | null    |
| Guillotine Choke                           | F     | FALSE | FALSE | null    |
| Headlock                                   | F     | FALSE | FALSE | null    |
| Hopping Rolling Pin                        | C     | FALSE | FALSE | null    |
| Hopping Sunset Flip Pin                    | C     | FALSE | FALSE | null    |
| Hurracanrana Pin                           | D     | FALSE | FALSE | null    |
| Judo Front Slam                            | E     | FALSE | FALSE | null    |
| Knee Smash                                 | C     | FALSE | FALSE | null    |
| Manhattan Drop                             | D     | FALSE | FALSE | null    |
| Michinoku Driver                           | C     | FALSE | FALSE | null    |
| Military Press                             | E     | FALSE | FALSE | null    |
| Northern Lights Suplex 01                  | C     | FALSE | FALSE | null    |
| Northern Lights Suplex 02                  | E     | FALSE | FALSE | null    |
| Oklahoma Slam                              | B     | FALSE | FALSE | null    |
| Powerbomp Pin 01                           | C     | FALSE | FALSE | null    |
| Powerbomp Pin 02                           | C     | FALSE | FALSE | null    |
| Powerbomp Pin 03                           | B     | FALSE | FALSE | null    |
| Powerbomp Pin 04                           | B     | FALSE | FALSE | null    |
| Powerbomp Pin 05                           | C     | FALSE | FALSE | null    |
| Powerbomp Pin 06                           | B     | FALSE | FALSE | null    |
| Powerbomp Pin 07                           | C     | FALSE | FALSE | null    |
| Powerbomp Pin 08                           | C     | FALSE | FALSE | null    |
| Powerbomp Pin 09                           | C     | FALSE | FALSE | null    |
| Powerslam                                  | D     | FALSE | FALSE | null    |
| Reverse Armbar                             | F     | FALSE | FALSE | null    |
| Reverse Suplex                             | D     | FALSE | FALSE | null    |
| Rolling Leg Lock                           | F     | FALSE | FALSE | null    |
| Rope Drop Clothesline                      | E     | FALSE | FALSE | null    |
| Running Knee Strike                        | E     | FALSE | FALSE | null    |
| Running Powerbomb Pin                      | C     | FALSE | FALSE | null    |
| Sambo Suplex                               | C     | FALSE | FALSE | null    |
| Scoop Piledriver                           | D     | FALSE | FALSE | null    |
| Shoulder Breaker Thrust                    | E     | FALSE | FALSE | null    |
| Sidewalk Slam                              | D     | FALSE | FALSE | null    |
| Small Package                              | C     | FALSE | FALSE | null    |
| Snap Powerbomb 01                          | C     | FALSE | FALSE | null    |
| Snap Powerbomb 02                          | C     | FALSE | FALSE | null    |
| Snap Powerbomb 03                          | C     | FALSE | FALSE | null    |
| Somersault Kick                            | F     | FALSE | FALSE | null    |
| Spinning Leg Takedown                      | C     | FALSE | FALSE | null    |
| Standing Armbar                            | F     | FALSE | FALSE | Submit  |
| Standing Clothesline                       | D     | FALSE | FALSE |         |
| Stalling Brainbuster                       | B     | FALSE | FALSE |         |
| Stalling Piledriver                        | C     | FALSE | FALSE |         |
| Strong Sambo Suplex                        | C     | FALSE | FALSE |         |
| Super Shoulder Breaker                     | B     | FALSE | FALSE |         |
| Sweep with Mounted Punching                | F     | FALSE | FALSE | Submit  |
| Tiger Driver                               | D     | FALSE | FALSE |         |
| Tiger Driver with Pin                      | C     | FALSE | FALSE | Pin     |
| Tilt A Whirl Piledriver                    | D     | FALSE | FALSE |         |
| Trapping Headbutts                         | E     | FALSE | TRUE  | null    |
| Triple Powerbomb Pin                       | C     | FALSE | FALSE | Pin     |
| Two Handed Choke Lift                      | E     | FALSE | FALSE | Submit  |
| T-Bone Suplex 01                           | D     | FALSE | FALSE | null    |
| T-Bone Suplex 02                           | C     | FALSE | FALSE | null    |
| Underhook Back Breaker                     | C     | FALSE | FALSE | null    |
| Underhook Belly to Belly Suplex 01         | C     | FALSE | FALSE | null    |
| Underhook Belly to Belly Suplex 02         | C     | TRUE  | FALSE | null    |
| Arm Dragon Screw                           | F     | FALSE | FALSE | null    |
| Arm Wrench / Elbow Smash                   | E     | FALSE | FALSE | null    |
| Arm Wrench with Hook Kick                  | E     | FALSE | FALSE | null    |
| Back Body Flip                             | E     | FALSE | FALSE | null    |
| Chop Down                                  | E     | FALSE | FALSE | null    |
| Drop Suplex 01                             | E     | FALSE | FALSE | null    |
| Drop Suplex 02                             | E     | FALSE | FALSE | null    |
| Double Underhook Suplex                    | E     | FALSE | FALSE | null    |
| Fallaway Slam                              | E     | FALSE | FALSE | null    |
| Falling Neck Breaker                       | E     | FALSE | FALSE | null    |
| Falling Powerslam                          | E     | FALSE | FALSE | null    |
| Falling Suplex                             | D     | FALSE | FALSE | null    |
| Gordbuster 01                              | E     | FALSE | FALSE | null    |
| Gordbuster 02                              | D     | FALSE | FALSE | null    |
| Headlock Takedown                          | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 01                   | E     | FALSE | FALSE | null    |
| Head Scissor Takedown 02                   | E     | FALSE | FALSE | null    |
| Hip Throw                                  | E     | FALSE | FALSE | null    |
| Hip Toss                                   | E     | FALSE | FALSE | null    |
| Jawbreaker                                 | F     | FALSE | FALSE | null    |
| Knee Strikes 01                            | F     | FALSE | FALSE | null    |
| Knee Strikes 02                            | F     | FALSE | FALSE | null    |
| Knee Strikes 03                            | E     | FALSE | FALSE | null    |
| Mini Chops                                 | E     | FALSE | FALSE | null    |
| Neck Breaker 01                            | E     | FALSE | FALSE | null    |
| Neck Breaker 02                            | E     | FALSE | FALSE | null    |
| Piledriver 01                              | D     | FALSE | FALSE | null    |
| Piledriver 02                              | E     | FALSE | FALSE | null    |
| Piledriver 03                              | D     | FALSE | FALSE | null    |
| Piledriver 04                              | D     | FALSE | FALSE | null    |
| Rib Breaker                                | E     | FALSE | FALSE | null    |
| Russian Leg Sweep                          | E     | FALSE | FALSE | null    |
| Shoulder Breaker                           | E     | FALSE | FALSE | null    |
| Shoulder Thrusts                           | E     | FALSE | FALSE | null    |
| Snap Suplex                                | E     | FALSE | FALSE | null    |
| Stall Suplex                               | E     | FALSE | FALSE | null    |
| Suplex                                     | E     | FALSE | FALSE | null    |
| Tie Up Knee Strikes                        | F     | FALSE | FALSE | null    |
| Underhook Suplex / Knee                    | D     | FALSE | FALSE | null    |

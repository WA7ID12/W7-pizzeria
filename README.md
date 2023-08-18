# W7-pizzeria
-----------------------------------------------------------------------------------------------------------------------------------------
   
    السكربت يشتغل على الكور الجديد           |

    واعتذر على قل الاشياء لاكن فيه واحد يبيعه وتعبان عليه ومقدر اسوي احسن منه او نفسه وانزله مجاناََ لان يعتبر كذا اني قطعت رزقه         |

    السكربت ما فيه ولا مشكلة لا تسوي مشكله وتجي تقول سكربتك خربان                                                                     |
-------------------------------------------------------------------------------------------------------------------------------------------






resources\[qb]\qb-core\shared -->items.lua
    --  w7-pizza
    ["tmeto1"] 				 = {["name"] = "tmeto1", 			 	["label"] = "طماطم شرايح", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "f_domates.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["shoclet"] 				 = {["name"] = "shoclet", 			 	["label"] = "نوتلا", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "nutela.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
	["pizzav"] 				 = {["name"] = "pizzav", 			 	["label"] = "بيدزا خضار", 					["weight"] = 250, 		["type"] = "item", 		["image"] = "capricciosa.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
	["ajen"] 				 = {["name"] = "ajen", 			 	["label"] = "عجين", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "wa7id44.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["cookies"] 			 = {["name"] = "cookies", 			 	["label"] = "Moneyshot", 				["weight"] = 300, 		["type"] = "item", 		["image"] = "cookie.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["ajen1"] 				 = {["name"] = "ajen1", 			 	["label"] = "عجين مفرود", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "wa7id33.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
	["pizzaw"] 				 = {["name"] = "pizzaw", 			 	["label"] = "بيدزا ببروني", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "diavola.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["tmeto"] 				 = {["name"] = "tmeto", 			 	["label"] = "طماطم", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "bs_tomato.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["bbrune"] 				 = {["name"] = "bbrune", 			 	["label"] = "ببروني", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "bbrone.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["pizzaw7"] 				 = {["name"] = "pizzaw7", 			 	["label"] = "بيدزا ببروني 2", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "eg_pizza-slice.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    
    ["pizzajb"] 				 = {["name"] = "pizzajb", 			 	["label"] = "بيدزا جبن", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "w7pizzajb.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    ["fradh"] 				 = {["name"] = "fradh", 			 	["label"] = "فراده", 					["weight"] = 310, 		["type"] = "item", 		["image"] = "wa7id55.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Sates Hunger."},
    -- w7- Drinks
	
	["colapa"] 			 = {["name"] = "colapa", 				["label"] = "Soft Drink", 				["weight"] = 125, 		["type"] = "item", 		["image"] = "d_cola.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "An Ice Cold Drink."},
	["sevenpa"] 			     = {["name"] = "sevenpa", 				["label"] = "Milkshake", 				["weight"] = 125, 		["type"] = "item", 		["image"] = "bsprite.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = "Hand-scooped for you!"},
	



--------------------------------------------------
--اسم الوضيفه تضيفه في    
resources\[qb]\qb-core\shared -->jobs.lua

        ['w7pizza'] = {
            label = 'w7pizza',
            grades = {
                ['0'] = {
                    name = 'عامل بيدزا'
                },

        
            }}
 ---------------------------------------------
resources\[qb]\qb-smallresources --> config.lua



     ["pizzaw"] = math.random(35, 54),
	["pizzaw7"] = math.random(35, 54),
	["pizzajb"] = math.random(35, 54),
    ["pizzav"] = math.random(35, 54),



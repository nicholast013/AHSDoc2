## Introduction

> Well its easy if you want to learn :)

> Iam making this easy :D

## Installation

> local dissys = require(game.ReplicatedStorage:WaitForChild("LimbModules"):WaitForChild("DiseaseSystem"))

## Adding Cough to your virus

> local cough = dissys.Cough(script.Parent) 

> Making loop coughing

```lua
while task.wait() do
        local char = dissys.Cough(char)
        if char then
            script:Clone(char)
        end
        wait(2)
    end
```

> Yes its real your not schizo and its simple to use :D

## Make body have bloody bubble

> dissys.bubble(charpart)

> Make full body have bubble

```lua
if char:FindFirstChild("Left Arm") then
	dissys.bubble( char["Left Arm"])
end
if char:FindFirstChild("Right Arm") then
	dissys.bubble( char["Right Arm"])
end

dissys.bubble(char["Left Leg"])
dissys.bubble(char["Right Leg"])
dissys.bubble(char.Torso)

dissys.bubble(char.Head)
```

## Make body covered in blood

> dissys.bodyblood(charpart)

> Make limb get painted with blood

```lua
if char:FindFirstChild("Left Arm") then
	dissys.bodyblood( char["Left Arm"])
end
if char:FindFirstChild("Right Arm") then
	dissys.bodyblood( char["Right Arm"])
end

dissys.bodyblood(char["Left Leg"])
dissys.bodyblood(char["Right Leg"])
dissys.bodyblood(char.Torso)

dissys.bodyblood(char.Head)
```

## Vommiting 

> dissys.vomit(char)

> You vomit and you got blur and damaged

```lua
dissys.vomit(char)
```

> Yeah its simple what did you even think?

## Temp Blur

> in template script on effects folder you can see a remote event and client script

> change 3 to whatever time you want

```lua
script.ClientEvent:FireClient(game:GetService("Players"):GetPlayerFromCharacter(char), "Blur", 3, char)
```

## Temp Slow

> in template script on effects folder you can see a remote event and client script

> change 3 to whatever time you want

```lua
script.ClientEvent:FireClient(game:GetService("Players"):GetPlayerFromCharacter(char), "Slow", 3, char)
```

## Tutorial

> First copy template from effects and go script now!

> After done rename the thing to whatever goofy name you want

> Then go to template on folder and add your virus to the template module

> Rename the template module to whatever name you wanted it to be

> Done!! 

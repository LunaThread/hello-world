# hello-world
First Git-Hub test project 

using Unity; 
using Fungus;

Public class extends monobehaviour (){

Var movement = 0.1f;
public bool idle;
public flowchart Flowchart;
private Animator anim;

}

void Public (); 
{
 if (player.component = true)
 {
    flowchart.setVariable(idle) = false; 
    anim.FreezeComponent;
 }
 else if 
 {
     flowchart.setVariable(idle) == true;
 }
}

// If bool is set to true, set variable to false, whereas if player bool component is set to false, set variable to true.

// This could be, for example, a player attack function. You switch off the idle bool because the player is attacking therefore is not idle, whereas if the player is not attacking, the idle bool would be set to true.

// You would have to have another function here which considers if the player is moving, in which the idle would be set to false, for example: 

if (player.movement > 0.1) 
{
    player.direction * time.DeltaTime (mathClamp.x, mathClamp y)
    {
     // if this function is being called, set the idle function to false 
     idle = false;
    }
    // Create a variable for the function movement. 
}

if (player.anim = getPlayState "attack")
{
 
mathClamp.x = thisPos.x;
mathClamp.y = -thisPos.y;

}


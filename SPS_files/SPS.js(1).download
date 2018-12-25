function ComputerPlay(playerSelection,computerSelection){
    //paper=1
    //stone =2
    //scissor =3
    if(playerSelection==1)
    {
        if(computerSelection==2)
        {
            return("Player Won");
        }else if(computerSelection==3)
        {
            return("Computer Won");
        }else{
            return("Draw");
        }
    }
    //stone
    if (playerSelection == 2) {
        if (computerSelection == 3) {
            return("Player Won");
        } else if (computerSelection == 1) {
            return("Computer Won");
        } else {
            return("Draw");
        }
    }
    //scissors
    if (playerSelection == 3) {
        if (computerSelection == 1) {
            return("Player Won");
        } else if (computerSelection == 2) {
            return("Computer Won");
        } else {
            return("Draw");
        }
    }
}
function getNamePlayer(playerSelection)
{
    switch(playerSelection)
    {
        case 1 : return("paper");
                 break;
        case 2: return("stone");
                break;
        case 3: return("scissors");
                break;
    }
}
function getNameComputer(computerSelection)
{
    switch(computerSelection)
    {
        case 1: return ("paper");
            break;
        case 2: return ("stone");
            break;
        case 3: return ("scissors");
            break;
    }
}
function checkClick(key)
{   
    let comKey = Math.floor(Math.random() * 3) + 1
    document.getElementById("demo").innerHTML = "Player chose " + getNamePlayer(key) + " \nComputer chose " + getNameComputer(comKey) + " \n " +  ComputerPlay(key,comKey);
}
function runFunction()
{
    let playerSelection = parseInt(prompt("Enter Choics\n1.Paper\n2.Stone\n3.Scissors"));
    let computerSelection = Math.floor(Math.random() * 3) + 1;
    ComputerPlay(playerSelection, computerSelection)
}
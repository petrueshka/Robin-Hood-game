# Robin-Hood-game
Little silly game for JavaScript practice

var user = prompt("Robin Hood meets the Sheriff. Choose if he -" , " should ROB, HUG or FLEE").toLowerCase();
switch(user){
    case "rob":
        console.log("CA-CHING! More cash to give to the poor.");
        break;
        case "hug":
            console.log("Ouch! You got Robin Hood killed :( ");
            break;
            case "flee":
                var drunk = prompt("Is the Sheriff drunk?", "type YES or NO").toLowerCase();
                var fat = prompt("Is the Sheriff fat?","YES or NO").toLowerCase();
                if (drunk === "yes" && fat === "yes"){
                    console.log("Beep - Beep! Off he runs. You saved Robin's arse!");
                }else if
                (drunk === "yes" || fat === "yes"){
                    console.log("Sheriff almost got him! Phew.");
                    }else{
                       console.log("Well done, genious. You got Robin Hood behind the bars. Are you working for that Sheriff?");
                    };
                break;
                default:
                console.log("Well... who knows what would happen if he " + user + "ed him?.. I don't.");
}

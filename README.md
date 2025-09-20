// === YOUR GAME LOGIC PART START ===
function generateRandomColor(){
    const colors = ['Red','Green','Blue'];
    const index = Math.floor(Math.random() * colors.length);
    return colors[index];
}

function checkResult(userPick){
    const outcome = generateRandomColor();
    const win = (userPick === outcome);
    return { outcome, win };
}
// === YOUR GAME LOGIC PART END ===

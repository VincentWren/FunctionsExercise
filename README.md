# FunctionsExercise
function fozzieBear() {
    console.log(`Wocka Wocka!`);
}

function beaker(speak){
    console.log(`${speak}`);
}
beaker(`Meep`);

function muppetShow(a, b, c){
    console.log(`${a} ${b} ${c}`);
}
muppetShow(`Muppet`, `Show,`, `It's time to play the music. It's time to light the lights.`);

function kermit() {
    console.log(`Kermit The Frog`);
}

const muppetShowSeasons = [1, 2, 3, 4, 5];
const muppetCheck = muppetShowSeasons.filter(m => m < 4); // not sure .<.
console.log(muppetShowSeasons);

function manOrMuppet(sadmusic) {
    console.log(`${sadmusic}`);
}
manOrMuppet(`Am I a man or am I a Muppet?`);

function rainbowConnection(rc) {
    rc();
}
rainbowConnection(()=> {
    console.log(`"Someday we'll find it. The Rainbow Connection. The lovers, the dreamers and me"`);
});

// yes(?)

// no(?)

const newMuppetMovies = [
    {One: `The Muppets`},
    {Two: `Muppets Most Wanted`}
]; 
newMuppetMoviesTwo = nmm => nmm.One + " " + nmm.Two{
    console.log(nmm.One.toUpperCase());
    console.log(nmm.Two.toUpperCase());
} // not sure either .^.
const upperMovies = newMuppetMoviesTwo.map(newMuppetMovies);
console.log(upperMovies); 

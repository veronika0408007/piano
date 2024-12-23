function toggleNotes() {
    document.querySelector('.piano').classList.toggle('show-notes');
}

const keys = document.querySelectorAll('.key');
keys.forEach(key => key.addEventListener('click', playNote));

function playNote() {
    const note = this.dataset.note;
    const audio = new Audio(`sounds/${note}.mp3`);
    audio.play();
}

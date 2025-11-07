Json API containing every currently recognized Bunaverse character

To access this API in a javascript project, use the following code:

const databankLink = 'https://raw.githubusercontent.com/2Pidds/Bunaverse-API/refs/heads/main/characters.json';
const res = await fetch(databankLink);
const databank = await res.json();

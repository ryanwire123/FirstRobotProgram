async function startProgram() {
	setMainLed({ r: 255, g: 0, b: 4 });
	await roll(0, 33, 3);
	setMainLed({ r: 255, g: 107, b: 0 });
	await roll(180, 33, 3);
	await roll(90, 33, 3);
	setMainLed({ r: 255, g: 168, b: 0 });
	await roll(270, 33, 3);
	await roll(180, 33, 3);
	setMainLed({ r: 254, g: 0, b: 255 });
	await roll(0, 33, 3);
	await roll(270, 33, 3);
	setMainLed({ r: 108, g: 0, b: 255 });
	await roll(90, 33, 3);
	setMainLed({ r: 0, g: 255, b: 48 });
	await speak('Pretty good right?', true);
	stopRoll();
}

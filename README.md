# ChromeThings

Dino Game:

  AntiGameOver: ```Runner.instance_.gameOver = () => {}``` works for all

  AntiGameOver: ```checkForCollision = () => {}``` works for only original dino game
  
  EndGame: ```Runner.instance_.gameOver()``` does not work with AntiGameOver hack
  
  SetSpeed: ```Runner.instance_.currentSpeed = ?```
  
  DistanceRan: ```Runner.instance_.distanceRan = ?```
  
  Jump: ```Runner.instance_.tRex.setJumpVelocity(?)```
  
  idkBreakTheGame: ```Runner.instance_.tRex.config = () => {}```
  
  dropVelocity: ```Runner.instance_.tRex.config.DROP_VELOCITY = ?``` stay in negatives
  
  noMoreObstacles: ```Horizon.prototype.addNewObstacle = () => {}``` only works with AntiGameOver hack
  
  fly: ```Runner.instance_.tRex.groundYPos = 10```
  
  setAcceleration: ```Runner.config.ACCELERATION = ?```
  
YoHoHo.io:

  Coins: ```localStorage.setItem("coinsOwned", ?);```
  
  Xp: ```localStorage.setItem("playerXP", ?);```
  
  Skin: ```localStorage.setItem("playerSkin", ?);```  1 to 35
  
  PetXp: ```localStorage.setItem("playerPet", ?);``` 1 to 9
  
  PetLevel: ```localStorage.setItem("playerPetLevel", ?);``` 1 to 14
  
  Fix: ```localStorage.clear()```

Lunar Lander:

  fuel: ```lander.fuel = ?```
  
  setScore: ```score = ?```
  
  endGame: ```setCrahsed()```
  
  neverCrash: ```setCrashed = () => {}```

Cookie Clicker:

  openSesame: ```Game.OpenSesame()```

  cookies: ```Game.cookies = ?```
  
  lumps: ```Game.lumps = ?```

spend elon fortune:
  setMoney: ```elonFortune = ?```

START
FUNCTIONS: STEAM = heat for 5 seconds
            STIR = stir for 5 seconds
            DING = bell sound
PROCESS: coffee ordered from Alexa
1. IF coffeeType = coffee
    print coffee
    doUntil : 8 oz. Enddo
    
    If coffeeType = espresso
    print espresso
    doUntil 1 shot Enddo

    Else = doNothing

2. IF coffeeAmount = double
    AND coffeeType = coffee
    PRINT 16 oz.

    IF coffeeAmount = double
    AND coffeeType = espresso
    PRINT 2 shots

    Else = PRINT regular

2. If flavor = vanilla
    PRINT 2 tbsp. vanilla

    If flavor = caramel
        PRINT 2 tbsp. caramel
    
    If flavor = hazelnut
        PRINT 2 tbsp. caramel

    Else: PRINT none

3. If topping = sugar

    PROCESS number

    PRINT

    ELSE = PRINT None

2. IF creamerType = skim
    call creamerAmount
    PRINT skim x creamerAmount

    IF creamerType = halfandhalf
    call creamerAmount
    PRINT halfandhalf x creamerAmount

    IF creamerType = almondmilk
    call creamerAmount
    PRINT almondmilk x creamerAmount

    IF creamerType = wholemilk
    call creamerAmount
    PRINT wholemilk x creamerAmount

    ELSE: END

    
3. IF creamerAmount = regular 
    PRINT 2 tbsp. creamer

    IF creamer = double
    PRINT 4 tbsp. creamer

    ELSE = doNothing

6. If coffeeType = espresso , creamerAmount = any

    INIT: STEAM

7. If coffeeType = any
    INIT: STIR
    INIT: DING

    Else: doNothing
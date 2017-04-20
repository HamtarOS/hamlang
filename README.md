# hamlang
The language powering HamtarOS

# Language Overview
hamlang is the interpreter, compiler, and name of the first-class supported
language in HamtarOS, the world's most advanced Hamtaro-based operating system.

hamlang is a multi-paradigm language supporting all of the best ways of programming
and finding adventure with your ham ham friends.

# Terminology

## Cage
The "cage" is the application's virtual memory space. The layout is as follows:

```
uhh
```

## Cage Cleaning
Similar to garbage collection in other languages, periodically the cage cleaner will run
and remove from the "cage" (the application's memory space) any hamsters who no longer have
burrows.

## Hamsters
For object-oriented style programming, hamlang has the concept of a "Hamster", which
is roughly analogous to "class" in other languages. A hamster definition might look
like the following:

```
🐹 Bijou {
  // ...
}
```

and the associated instantiation like this:

```
myFriendBijou := new 🐹 Bijou
```

## Ham Hams
An instance of a Hamster is known as a "Ham Ham".

## Whiskers
What other languages might call "object properties" are known as "whiskers" in hamlang.

## Habitat
A habitat is what would, in traditional 20th century computing, be known as a "program".

## Cheeks
Cheeks store things.

## Tubes
Ham Hams use tubes to communicate with their friends in other cages.

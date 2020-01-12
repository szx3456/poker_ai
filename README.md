# Open Source Pluribus Implementation

This repository will contain a best effort implementation of the key ideas from the Pluribus poker AI bot. 

## Very rough todo

The following todo will change dynamically as my understanding of the algorithms and the pluribus project evolves. 

At first prototype in Python (easier).
- Implement a multiplayer working heads up no limit poker game.
- Implement the pluribus algorithms. 

Once there is a working prototype, write in a systems level language like C++ and optimise for performance. 

## Structure

```
├── paper    # main source of info and documentation
└── pluribus # python code
    ├── ai   # (currently) python stubs for ai algorithms.
    └── game # wip code for managing a hand of poker
```

## Contributing

This is an open effort and help, criticisms and ideas are all welcome. Feel free to start a discussion on the github issues or to reach out to me at leonfedden at gmail dot com. 

## Useful links
* [Paper](https://www.cs.cmu.edu/~noamb/papers/19-Science-Superhuman.pdf)
* [Supplimentary Material](https://science.sciencemag.org/highwire/filestream/728919/field_highwire_adjunct_files/0/aay2400-Brown-SM.pdf)
* [Facebook blog post](https://ai.facebook.com/blog/pluribus-first-ai-to-beat-pros-in-6-player-poker/)
* [Hacker News Discussion](https://news.ycombinator.com/item?id=20415379)
* [Other github discussions](https://github.com/whatsdis/pluribus)
* [Game code based on this (dead!?!) repo](https://pypi.org/project/pluribus-python/#data)

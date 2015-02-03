# mkcast

This branch is a little modification of KeyBoardFire's master, designed to work with a little more work and a little less automation, but on the tiling window manager Xmonad. If I knew more haskell/Xmonad, I might be able to have done a bit better. But so it goes!

The problems this overcomes are the following:

1. screenkey would not start immediately for me before
2. the screenkey window would really mess with the tiling window manager
3. I wanted to know exactly when the recording started and ended

This introduces new problems:

1. You must start screenkey and resize it beforehand

(This is a very annoying problem)

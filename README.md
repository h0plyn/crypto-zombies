# Crypto Zombies

An exercise in learning more about Solidity through game development

1. [Lesson 1 Zombie](https://share.cryptozombies.io/en/lesson/1/share/h0plynprotonmail.com)
2. [Lesson 2 Zombie](https://share.cryptozombies.io/en/lesson/2/share/h0plynprotonmail.com)
3. [Lesson 3 Zombie](https://share.cryptozombies.io/en/lesson/3/share/h0plynprotonmail.com)
4. [Lesson 4 Zombie](https://share.cryptozombies.io/en/lesson/4/share/h0plynprotonmail.com?id=W251bGwsMSwxNF0=)
5. [Lesson 5 Zombie](https://share.cryptozombies.io/en/lesson/5/share/H4XF13LD_MORRIS_💯💯😎💯💯)

### natspec comment standard

```
/// @title A contract for basic math operations
/// @author H4XF13LD MORRIS 💯💯😎💯💯
/// @notice For now, this contract just adds a multiply function
contract Math {
  /// @notice Multiplies 2 numbers together
  /// @param x the first uint.
  /// @param y the second uint.
  /// @return z the product of (x * y)
  /// @dev This function does not currently check for overflows
  function multiply(uint x, uint y) returns (uint z) {
    // This is just a normal comment, and won't get picked up by natspec
    z = x * y;
  }
}
```

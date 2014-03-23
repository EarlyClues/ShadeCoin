ShadeCoin
=========

Units of exchange designed specifically for use on the abstractions/symbols/synconjury market.
Individual units are stored in our open source LiminalVault, and their total value can be read/displayed electronically.

Installation
============

The easiest way to get started is to compile & run the Generator code. The entire ShadeCoin Public API is contained within, but with jut a few lines of [OpenQNL](http://github/com/EarlyClues/OpenQNL) *anyone* can instantly have their overnight deposit box mining ShadeCoin on `sleep()`.

1. Download the OpenQNL repository: [OpenQNL](http://github/com/EarlyClues/OpenQNL)
2. Compile and link the OpenQNL dynamic library into the host project ( OpenQNL currently has ports for
every major language & platform. Full a full list of compatibly host environments, please see our OpenQNL wiki). >Currently not working with JavaME or JNI bridge, Richard Rider, Sept 1, 2002)
3. Annotate relevant source files with our `@summon` keyword to further bind source code to our interpreter and including required libraries Annotations may be marker annotations, single-valued annotations, or multi-valued annotations.

*Example

```

@summon '_universal_free_realm_standard_protocol'
@summon '_open_qnl'
@summon '_shadecoin_generator'
@summon 'listener'
@summon 'current_user'
public static void _signature(unsigned int parameter_1) {
  // do legacy work
  // ShadeCoin hook...  (takes a block&)
}
```

4. Call any of the methods in the public API. Access is locally scoped.

Public API Specification
=================

`void sleep()`

`void wake()`

`void deposit_shade_coin(ShadeCoin coin)`

`signed int validate_shade_coin(ShadeCoin coin)`

`char[] display_shade_coins()`

`ShadeCoin generate_shade_coin()`

`void spend_shade_coin(Shadecoin coin)`


Supplemental
============

If you’re in too much of a rush to wait for fulfillment one of our affiliates has prepared a demonstration of how to use a ShadeCoin.

https://www.youtube.com/watch?v=N5AKCHyQccQ
>Note: This video demonstration is actually how to spend a ShadeCoin, but if you have no ShadeCoins, you may duplicate this process by exchanging the ShadeCoin pictured below for “actual currency” from your region, and depositing it in the machine. You will be automatically reimbursed in the form of a random ShadeCoin of equal or greater value within three Buorthern Business Days.

# Dead Man's Switch Vault

## Introduction
This dapp would allow an user to create a vault a deposit funds in it. Each vault will have a beneficiary (another EOA presumibly). The vault will have a dead man's switch (aka a timer) that will reset every time the owner of the account interacts with the vault. In the case that the timer runs out, the funds of the vault will be transferred to the beneficiary. It is thought as an automated inheritance system.

## Basic Functionality
- An user should be able to create a vault and deposit funds.
- An user should be able to add/withdraw funds from existing vaults.
- An user should be able to add/modify the beneficiary.
- An user should be able to reset the Dead Man's Switch (timer).
- An user should be able to set the timer duration.



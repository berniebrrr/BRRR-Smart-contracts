# BRRR-Smart-contracts
BRRR.fi smart contracts
<div id="ethdoc-viewer">

### BRRR contract docs

**Functions**

* * *

###### constructor - read

Sets the values for {name} and {symbol}, initializes {decimals} with a default value of 18\. * Sets the total supply from tether * Gives founding father liquidity share for uniswap * Sets first supply check

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>name</td>

<td>string</td>

<td></td>

</tr>

<tr>

<td>symbol</td>

<td>string</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

* * *

###### DEFAULT_ADMIN_ROLE - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### EmergencyWithdrawalCoins - read

In case of emgergency - withdrawal all coins. * Contract must be offline *

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_contract</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### EmergencyWithdrawalETH - read

In case of emgergency - withdrawal all eth. * Contract must be offline *

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### FOUNDING_FATHER - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### Online - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### TOTALCAP - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### TreasuryReserve - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _acceptedStableCoins - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _all_Claim_ids - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint128</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _all_Claims - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint128</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_amount</td>

<td>uint256</td>

<td></td>

</tr>

<tr>

<td>_ending</td>

<td>uint256</td>

<td></td>

</tr>

<tr>

<td>_amount_to_give</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _all_supply_checks - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_last_check</td>

<td>uint256</td>

<td></td>

</tr>

<tr>

<td>_totalSupply</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _circulatingSupply - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _claimed_stimulus - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

<tr>

<td></td>

<td>uint128</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _coin_deposits - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _deposits_eth - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### _total_withdrawals - read

****Add Documentation for the method here****

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### addAcceptedStableCoin - read

Adds another token to the accepted coins for printing * Calling conditions: * - Address of the contract to be added - Only can be added by founding fathers

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_contract</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>_oracleAddress</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### addStimulus - read

Adds stimulus package to be claimed by users * Calling conditions: - Only can be added by founding fathers

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_id</td>

<td>uint128</td>

<td></td>

</tr>

<tr>

<td>_total_amount</td>

<td>uint256</td>

<td></td>

</tr>

<tr>

<td>_ending_in_days</td>

<td>uint256</td>

<td></td>

</tr>

<tr>

<td>_amount_to_get</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### allowance - read

See {IERC20-allowance}.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>owner</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>spender</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### approve - read

See {IERC20-approve}. * Requirements: * - `spender` cannot be the zero address.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>spender</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>amount</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### balanceOf - read

See {IERC20-balanceOf}.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>account</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### brrr10x - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### brrr3x - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### brrrEvent - read

Update the total supply from tether - if tether has changed total supply. * Makes the money printer go brrrrrrrr Reward is given to whoever updates

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### calculateCurve - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### cap - read

Returns the cap on the token's total supply.

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### claimStimulus - read

Claim a stimulus package. * requires _id of stimulus package. Calling conditions: - can only claim once - must not be ended - must not be out of funds.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_id</td>

<td>uint128</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### convertBrrrXintoBrrr - read

Transfers entire brrrX balance into brrr at 1 to 1 Deposits on brrrX will not be cleared. *

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decimals - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint8</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### decreaseAllowance - read

Atomically decreases the allowance granted to `spender` by the caller.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>spender</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>subtractedValue</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### getRoleAdmin - read

Returns the admin role that controls `role`. See {grantRole} and {revokeRole}. * To change a role's admin, use {_setRoleAdmin}.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### getRoleMember - read

Returns one of the accounts that have `role`. `index` must be a value between 0 and {getRoleMemberCount}, non-inclusive. * Role bearers are not sorted in any particular way, and their ordering may change at any point. * WARNING: When using {getRoleMember} and {getRoleMemberCount}, make sure you perform all queries on the same block. See the following https://forum.openzeppelin.com/t/iterating-over-elements-on-enumerableset-in-openzeppelin-contracts/2296[forum post] for more information.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

<tr>

<td>index</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### getRoleMemberCount - read

Returns the number of accounts that have `role`. Can be used together with {getRoleMember} to enumerate all bearers of a role.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### grantRole - read

Grants `role` to `account`. * If `account` had not been already granted `role`, emits a {RoleGranted} event. * Requirements: * - the caller must have ``role``'s admin role.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

<tr>

<td>account</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

* * *

###### hasRole - read

Returns `true` if `account` has been granted `role`.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

<tr>

<td>account</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### increaseAllowance - read

Atomically increases the allowance granted to `spender` by the caller.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>spender</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>addedValue</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### name - read

Returns the name of the token.

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>string</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### printWithETH - read

Deposit eth and get the value of brrr based off bonding curve *

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### printWithStablecoin - read

Deposit alt coins and get the value of brrr based off bonding curve *

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_contract</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>_amount</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### renounceRole - read

Revokes `role` from the calling account. * Roles are often managed via {grantRole} and {revokeRole}: this function's purpose is to provide a mechanism for accounts to lose their privileges if they are compromised (such as when a trusted device is misplaced). * If the calling account had been granted `role`, emits a {RoleRevoked} event. * Requirements: * - the caller must be `account`.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

<tr>

<td>account</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

* * *

###### returnBrrrForCoins - read

Deposit brrr and get the value of alt coins for that amount of brrr based off bonding curve *

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_contract</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### returnBrrrForETH - read

Deposit brrr and get the value of eth for that amount of brrr based off bonding curve *

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### revokeRole - read

Revokes `role` from `account`. * If `account` had been granted `role`, emits a {RoleRevoked} event. * Requirements: * - the caller must have ``role``'s admin role.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>role</td>

<td>bytes32</td>

<td></td>

</tr>

<tr>

<td>account</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

No parameters

* * *

###### setBrrrXAddress - read

Set brrrX addresses. One time, cannot be changed. * Must be admin *

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>_brrr3xcontract</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>_brrr10xcontract</td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### symbol - read

Returns the symbol of the token, usually a shorter version of the name.

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>string</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### tether - read

****Add Documentation for the method here****

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>address</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### toggleOffline - read

In case of emgergency - turn offline. * Must be admin *

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### totalSupply - read

See {IERC20-totalSupply}.

No parameters

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transfer - read

See {IERC20-transfer}. * Requirements: * - `recipient` cannot be the zero address. - the caller must have a balance of at least `amount`.

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>recipient</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>amount</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

* * *

###### transferFrom - read

See {IERC20-transferFrom}. * Emits an {Approval} event indicating the updated allowance. This is not required by the EIP. See the note at the beginning of {ERC20}; * If address is approved brrr3x or brrr10x address don't check allowance and allow 1 transaction transfer (no approval needed)

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>sender</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>recipient</td>

<td>address</td>

<td></td>

</tr>

<tr>

<td>amount</td>

<td>uint256</td>

<td></td>

</tr>

</tbody>

</table>

Returns:

<table class="table table-sm table-bordered table-striped">

<thead>

<tr>

<th>Name</th>

<th>Type</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td></td>

<td>bool</td>

<td></td>

</tr>

</tbody>

</table>

</div>

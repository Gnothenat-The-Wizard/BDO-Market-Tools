# BDO-Market-Tools

## What is this?

This is a tool designed for placing large orders on the market over the preorder limit.
If an order place is over the standard preorder limit this CLI will collect the order automatically and place another order until the desired number to be brought is reached.
Another feature of this tool is to allow you to sell through larger stacks of items than those that can be listed at once.
The tool will collect the silver from you listing and re-list another stack until the desired number to be sold has been reached.

## User details
In order to use this tool you need to set some details that will allow the tool to make requests to the Markets API on your behalf.
In general it is not a good idea to share these details as with them someone could empty you marketplace by selling all items. Then, buying items and relisting them for less silver to drain your marketplace of silver.
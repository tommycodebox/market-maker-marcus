# Market Making Bot - Marcus

Simple market making bot that every 5 seconds decides on either buying or selling based on price conditions, while canceling unfulfilled orders and placing new ones to keep up to minimum set open orders. Also bot uses prices that range in the best 5% and checks available bid/ask liquidity before posting orders, that might exceed it. For each trade bot uses 10% of available token balance, which amongst other things can be adjusted in config file.

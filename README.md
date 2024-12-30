# Referral System on the Internet Computer

## Overview
The referral system is designed to manage referral relationships on the Internet Computer using Motoko. Each user can refer others, and both the referrer and the referee can benefit from the system by earning rewards based on the number of referrals and their associated multiplier.

The system stores a tree of referrals, where each user (node) has a unique referral code, a multiplier based on the number of direct and indirect referrals, and earnings based on these referrals.

## Features
- **Referral Code Generation**: Each user has a unique referral code generated based on a cosmic word list and a short UUID.
- **Referral Linking**: Users can link their accounts by providing a referral code.
- **Referral Earnings Calculation**: Earnings are calculated based on the number of referrals and the associated multiplier.
- **Referral Tree**: Users can view their referral tree, which includes both direct and indirect referrals.
- **Referral Count and Multiplier Calculation**: You can get the count of referrals for a given user, along with the multiplier and total earnings.
- **System Upgrade Support**: The system supports pre and post-upgrade functions to persist data.

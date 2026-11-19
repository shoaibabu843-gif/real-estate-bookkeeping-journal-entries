# Real Estate Bookkeeping: Journal Entries for QuickBooks Online

Worked examples for the transactions real estate investors record most often, using the accounts from [qbo-real-estate-chart-of-accounts](https://github.com/shoaibabu843-gif/qbo-real-estate-chart-of-accounts). Every example balances, and every amount is made up.

In QuickBooks Online most of these can be entered as regular transactions (deposits, expenses, checks, transfers) instead of journal entries. The debits and credits are the same either way. Always tag the property's class or location.

## Contents

1. Rent received
2. Security deposit received and returned
3. Mortgage payment: principal, interest and escrow
4. Property tax paid from escrow
5. Buying a rental property from the closing statement
6. Annual depreciation
7. Fix and flip: purchase, rehab and sale
8. Repair or improvement?

## 1. Rent received

The tenant at 123 Oak St pays $1,800 rent.

| Account | Debit | Credit |
|---|---:|---:|
| 1000 Operating Checking | 1,800 | |
| 4000 Rental Income | | 1,800 |

## 2. Security deposit received and returned

A security deposit belongs to the tenant until the lease ends, so it is a liability, not income.

**Received:** $1,500 deposited into the security deposit account.

| Account | Debit | Credit |
|---|---:|---:|
| 1010 Security Deposit Account | 1,500 | |
| 2200 Tenant Security Deposits Held | | 1,500 |

**Move-out:** $1,200 refunded to the tenant and $300 kept for damages.

| Account | Debit | Credit |
|---|---:|---:|
| 2200 Tenant Security Deposits Held | 1,500 | |
| 1010 Security Deposit Account | | 1,200 |
| 4030 Other Tenant Income | | 300 |

Then transfer the $300 kept from the security deposit account to operating checking.

## 3. Mortgage payment

A $1,800 payment: $400 principal, $950 interest and $450 escrow. Take the split from the lender's statement every month, because it changes.

| Account | Debit | Credit |
|---|---:|---:|
| 2500 Mortgages Payable | 400 | |
| 6070 Mortgage Interest | 950 | |
| 1300 Mortgage Escrow | 450 | |
| 1000 Operating Checking | | 1,800 |

## 4. Property tax paid from escrow

The lender pays the $2,400 property tax bill out of escrow.

| Account | Debit | Credit |
|---|---:|---:|
| 6110 Property Taxes | 2,400 | |
| 1300 Mortgage Escrow | | 2,400 |

## 5. Buying a rental property

From the closing statement:

- Purchase price $300,000
- Closing costs added to the cost of the property (title, recording, transfer tax) $6,000
- Lender origination fee $2,250
- New mortgage $225,000
- Earnest money paid before closing $5,000
- Land is 20% of the value, using the tax assessor's land-to-building ratio

Working:

- Land: 20% × $306,000 = $61,200
- Building: 80% × $306,000 = $244,800
- Cash due at closing: $300,000 + $6,000 + $2,250 − $225,000 − $5,000 = $78,250

| Account | Debit | Credit |
|---|---:|---:|
| 1500 Land | 61,200 | |
| 1510 Buildings | 244,800 | |
| 1600 Loan Costs | 2,250 | |
| 2500 Mortgages Payable | | 225,000 |
| 1320 Earnest Money Deposits | | 5,000 |
| 1000 Operating Checking | | 78,250 |
| **Total** | **308,250** | **308,250** |

Prorations on the closing statement (rent, property tax, prepaid interest, insurance) are not part of the property's cost. Record them to their own income and expense accounts. Loan costs are amortized over the life of the loan.

## 6. Annual depreciation

Residential rental buildings are depreciated straight-line over 27.5 years. Land is never depreciated, and improvements and appliances have their own recovery periods.

A full year on the $244,800 building: $244,800 ÷ 27.5 = $8,902 (rounded).

| Account | Debit | Credit |
|---|---:|---:|
| 8000 Depreciation Expense | 8,902 | |
| 1590 Accumulated Depreciation | | 8,902 |

The first and last years use the mid-month convention, so take the exact figures from your CPA's depreciation schedule.

## 7. Fix and flip

A flip is held for sale, so its costs build up in an asset account (Work in Progress) and reach the P&L only when it sells. Tag everything with the property's class or project. The [flip-job-cost-tracker.csv](flip-job-cost-tracker.csv) file in this repo follows the same example line by line.

**Purchase:** price $160,000 plus $3,000 closing costs, with a $128,000 hard money loan.

| Account | Debit | Credit |
|---|---:|---:|
| 1310 Flip Properties - Work in Progress | 163,000 | |
| 2300 Hard Money Loans | | 128,000 |
| 1000 Operating Checking | | 35,000 |

**Rehab:** $27,000 paid to contractors and for materials.

| Account | Debit | Credit |
|---|---:|---:|
| 1310 Flip Properties - Work in Progress | 27,000 | |
| 1000 Operating Checking | | 27,000 |

**Sale:** sold for $250,000, with a $12,500 commission and $2,500 closing costs. The hard money loan is paid off from the proceeds.

| Account | Debit | Credit |
|---|---:|---:|
| 1000 Operating Checking | 107,000 | |
| 5010 Selling Costs | 15,000 | |
| 2300 Hard Money Loans | 128,000 | |
| 4100 Property Sales | | 250,000 |

**Move the cost to the P&L:**

| Account | Debit | Credit |
|---|---:|---:|
| 5000 Cost of Property Sold | 190,000 | |
| 1310 Flip Properties - Work in Progress | | 190,000 |

**Result:** $250,000 − $190,000 − $15,000 = **$45,000 gross profit** on the flip.

Interest, property tax, insurance and utilities paid while you hold a flip are often added to Work in Progress too. Ask your CPA how they want holding costs treated.

## 8. Repair or improvement?

| Repair: expense it now | Improvement: capitalize and depreciate |
|---|---|
| Fixing a leak in the roof | Replacing the whole roof |
| Patching drywall | Adding a bathroom |
| Replacing a broken window pane | Replacing all the windows |
| Servicing the HVAC | Installing a new HVAC system |

Small purchases can often be expensed under the IRS de minimis safe harbor election ($2,500 per invoice or item for most small businesses). Your CPA makes the final call.

---

These examples are for bookkeeping practice and are not tax advice.

**Need your real estate books set up or cleaned up?** I'm Md Abu Shoaib, a QuickBooks Online bookkeeper for real estate investors and property managers.
👉 [Hire me on Upwork](https://www.upwork.com/freelancers/~011eae234a1e1ba092)

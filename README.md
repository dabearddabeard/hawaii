# Hawaii

## Command and Base Information

**Command**: 3rd Marine Littoral Regiment, 3rd Marine Division, Kaneohe Bay, HI [130]
**Base**: Kaneohe Bay Hawaii Marine Corps Base

Information: 
- [**Naval Clinic Hospital Kaneohe Bay Information**](http://www.med.navy.mil/sites/nhch/Pages/default.aspx)
    - Quarterdeck: 1-808-257-3365 x123
    - Appointments: 1-808-473-0247
    - After Hours Help: 1-808-473-0247 x3
- [**Commissary**](http://www.commissaries.com/stores/html/store.cfm?dodaac=HQCWHV): Open 7 days a week 10:00am-6:00pm Sat-Mon and 10:00am-7:00pm Tue-Fri.
- [**Exchange**](http://mccshawaii.com/retail/): MCX aboard Kaneohe is small but the Navy Exchange (NEX) is only 5 years old. 
- [**Cars**](): The government will pay to ship one of your vehicles to Hawaii. If you want to ship more than one vehicle it will be at your expense. From the west coast it will cost around $1,000 and from the east coast it will cost around $2,000. The price depends on the type of vehicle you are shipping. Some families opt to store their second vehicle on the mainland. It is possible to survive a tour with one vehicle especially if you live on base. For those that prefer two vehicles, many opt to purchase an inexpensive vehicle (an island car) from the lemon lot on base.
- **Pets**: There is a quarantine for all pets brought into Hawaii, but the waiting period will be substantially less if you do your homework in advance and are prepared for the requirements
    - The DoD will reimburse up to $550 to help against the costs of quarantine for your animal.
    - To quarantine for 5 days or less, [click for the requirements](http://hdoa.hawaii.gov/ai/aqs/faq-for-five-day-or-less-program/). If you don’t pass those guidelines, your pet may be quarantined for up to 120 days.
    - [Brochure and Prohibited Animals](http://hdoa.hawaii.gov/ai/files/2013/01/aqsbrochure.pdf)
- [**Pool**](http://www.mccshawaii.com/aquatics): A brand new year round pool (main pool) has just been opened on base and there are 4 other pools to utilize on base as well.
- **Hourly Child Care Care**: Available by reservation for children 6 weeks+.
    - Walk-ins are accepted on a space available basis.
    - Everyone must be preregistered for information and reservations.
    - Phone: 1-808-257-8354
- [**Manawale’s Riding Center**](http://www.manawalea.org/): Hippotherapy (horse therapy)
- [**Religious Services**](https://www.mcbhawaii.marines.mil/Offices-Staff/Chaplain): Base Chapel website

## Military Housing for Kaneohe Bay Hawaii Marine Corps Base

[**Apply**](http://www.ohanamarinecorpscommunities.com/application) to housing as soon as we get orders because the wait list can be months.
- Many of these homes have ocean views or are just blocks from the beach.
- Excellent community of spouses
- utilities included

[Ohana Military Communities](https://www.ohanamarinecorpscommunities.com/find-a-home?rank=13&dependents=3&form_action=active-duty): Search by rank 


## Inbound 

- Arriving With Family: Make reservations at [The Inns of the Corps](https://goo.gl/maps/mUwxC7tu7cCzGZfy8), the temporary lodging facility on MCBH. If the Inns of the Corps are unavailable, request a statement of non-availability from them.
    - Any non-military lodging must be vetted through the TLA office to ensure that it is TLA-approved lodging.
- Family Housing Office and Installation Personnel Administration Center (IPAC): Must report within three working days of arrival.
    - Copies of endorsed original orders.
    - Detaching and reporting endorsement.
    - Travel vouchers/documents.
    - Per MCO 11000.22, all Military Personnel inbound to MCBH must report to the Family Housing Office before entering into an off-base lease agreement or purchasing a home.
- [YouTube MCBH New Arrival Video](https://youtu.be/zBliWTzeX6M?si=G3_kXlu1kp16NjO-)

## Basic Allowance for Housing (BAH) 

Should we receive a BAH, expand the information provided below.

<details>
  <summary>CLICK TO EXPAND</summary>

- **Military Housing Allowance Area:** Honolulu County, HI (HI408)
- **ZIP Code:** 96863
- **CY24 O-4 with Dependents Allowance:** $4,380

If you are planning to live off base, visit [www.Homes.mil](www.Homes.mil).

### VA Loan Benefits

- No down payment requirement
- Absence of Private Mortgage Insurance (PMI)
- Competitive interest rates

### Monthly Budget Breakdown
- **Total Monthly Budget:** $4,380
- **Utilities:** $711.87
- **Remaining for Mortgage, Taxes, and Insurance:** $4,380 - $711.87 = $3,668.13

### Calculating Property Taxes and Insurance
- **Annual Property Taxes and Insurance Rate:** 1.55%
- Estimating on a monthly basis, divide the annual rate by 12.

### Mortgage Details
- **Interest Rate:** 3.5% annually
- **Loan Term:** 30 years (360 months)
- **Down Payment:** $0

```python

# Initialize constants
TOTAL_MONTHLY_BUDGET = 3668.13
ANNUAL_TAX_INSURANCE_RATE_DECIMAL = 1.55 / 100  # Convert percentage to decimal
ANNUAL_INTEREST_RATE_DECIMAL = 3.5 / 100  # Convert percentage to decimal
LOAN_TERM_YEARS = 30
LOAN_TERM_MONTHS = LOAN_TERM_YEARS * 12

# Calculate the monthly cost of property tax and insurance
# Note: This calculation assumes the loan amount equals the home value
HOME_VALUE_PLACEHOLDER = 100  # Placeholder for calculating rate impact
annual_tax_and_insurance = HOME_VALUE_PLACEHOLDER * ANNUAL_TAX_INSURANCE_RATE_DECIMAL
monthly_tax_and_insurance = annual_tax_and_insurance / 12

# Calculate the monthly mortgage payment, excluding taxes and insurance
monthly_mortgage_payment_excl = TOTAL_MONTHLY_BUDGET - monthly_tax_and_insurance

# Determine the monthly interest rate
monthly_interest_rate = ANNUAL_INTEREST_RATE_DECIMAL / 12

# Calculate the loan amount using the mortgage payment formula:
# P = (r * PV) / (1 - (1 + r)^-n), where P is the monthly payment, r is the monthly interest rate,
# PV is the present value (loan amount), and n is the loan term in months.
# The formula is rearranged to solve for PV (loan amount).
loan_amount = monthly_mortgage_payment_excl * (1 - (1 + monthly_interest_rate) ** -LOAN_TERM_MONTHS) / monthly_interest_rate

# Output the calculated loan amount
print(f"Calculated Loan Amount: {loan_amount}")
# Calculated Loan Amount: 816845.3904291481

```

Based on the provided information and calculations, the home loan amount, considering the total budget of $3,668.13 for mortgage, taxes, and insurance, is approximately **$816,845.39**

</details>

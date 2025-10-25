# Ecommerce-Funnel-Conversion-Optimization
E-commerce funnel analysis analyzing major conversion drop-offs on the Google Merchandise Store. Built a live Looker Studio dashboard to visualize the friction points and recommend specific UX improvements.

## 1. Project Goal & Methodology (Step A)
The objective was to identify the single largest user drop-off point in the standard e-commerce purchase path and scope the problem for an optimization project.

### Methodology & Evidence
| Component | Detail | Setting Used |
| :--- | :--- | :--- |
| **Data Source** | GA4 Demo Account (Google Merchandise Store) | Last 90 Days |
| **Analysis Tool** | GA4 Funnel Exploration Report | **Closed Funnel** (Users must enter at Step 1) |
| **Funnel Path** | 1. **Session Start** → 2. **View Product Page** → 3. **Add to Cart** → 4. **Begin Checkout** → 5. **Purchase** | All steps set to **"indirectly followed by"** to account for user browsing. |

<img width="1440" height="900" alt="Screenshot 2025-10-25 at 3 34 03 PM" src="https://github.com/user-attachments/assets/f9836956-e926-439c-9904-b6e79e897f52" />

### Initial Finding (The Leak)
The largest drop-off in the E-commerce Purchase Funnel (for the last 90 days) occurs between the 'View Product Page' (Step 2) and 'Add to Cart' (Step 3), with a total abandonment rate of 66%.

## 2. Problem Diagnosis & Segmentation (Step B)
To determine the root cause of the 66% abandonment, the funnel was segmented by device and channel to find the most and least efficient user groups.

### Methodology & Evidence
| Dimension | Primary Finding (The Evidence) | Strategic Conclusion |
| :--- | :--- | :--- |
| **Device Category** | **Mobile** users abandoned at **75.6%**, confirming a severe **Mobile UX** issue. | **Hypothesis:** The primary bottleneck is Mobile UX Friction. |
| **Session Default Channel Group** | **Search Traffic** (Organic/Paid) had **~12 percentage points higher abandonment** than high-intent Direct traffic 59.9%. | **Hypothesis:** Traffic Quality is Low. Search campaigns are acquiring low-intent, unqualified users. |

Device Category:

 <img width="891" height="324" alt=" " src="https://github.com/user-attachments/assets/fb6932ff-2c10-40e8-ba9d-cd801f055bf6" />

Session Default Channel Group:

<img width="898" height="405" alt="Screenshot 2025-10-25 at 4 02 50 PM" src="https://github.com/user-attachments/assets/65a74310-5759-4512-8acb-653c27ac2fdd" />

### Actionable Hypothesis
The overall 66.0% abandonment rate between the 'View Product Page' and 'Add to Cart' is driven by a critical, two-part failure:

1. Systemic Mobile UX Friction: Mobile users are the worst-performing segment, demonstrating significantly elevated abandonment at both the initial product page 75.6% and the subsequent Add to Cart to Checkout transition 56.6%. This confirms a severe, systemic mobile user experience (UX) problem that is creating continuous friction throughout the funnel.
2. Search Traffic Misalignment: Traffic arriving via Organic Search (72.1% drop-off) and Paid Search (72.2% drop-off) is consistently less qualified than Direct traffic (59.9% drop-off). This indicates a misalignment where search campaigns are acquiring low-intent users whose expectations are not being met by the product pages.

The data dictates that the highest-priority action is a Mobile UX Audit and optimization effort to immediately capture value from the 75.6% of mobile users currently being lost.




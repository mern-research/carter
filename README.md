<img src="https://github.com/mern-labs/carter/assets/129014318/538eb8e9-400d-45b4-8ae7-288e3cd6510b" width="auto" height="150">


## Carter 1.0.0
Carter is an advanced credit decision engine, meticulously crafted to serve the nuanced needs of financial institutions. At its core, Carter integrates a quartet of sophisticated subsystems, each powered by a specialized machine learning model, tailored to execute distinct facets of the credit risk assessment process. These models work in concert to evaluate Probability of Default (PD), Loss Given Default (LGD), Exposure at Default (EAD), and subsequently, compute the Expected Credit Loss (ECL), providing a comprehensive risk profile for each credit application.

# PD Core: 
Utilizing state-of-the-art algorithms, the PD core harnesses historical data to predict the likelihood of a borrower defaulting. It intricately analyzes borrower-specific variables and market trends, employing advanced feature engineering techniques to enhance prediction accuracy.

# LGD Core: 
The LGD subsystem delves into estimating the potential loss severity in the event of a default, taking into account collateral valuations, recovery rates, and legal considerations. This core is adept at adapting to varying recovery scenarios, ensuring precise loss estimations.

# EAD Core: 
Focused on quantifying the total exposure at the time of default, the EAD core meticulously accounts for outstanding balances, committed but undrawn funds, and potential future drawdowns, offering a clear picture of the financial stakes involved.

# ECL Calculation Core: 
Seamlessly synthesizing the outputs from the PD, LGD, and EAD cores, this subsystem computes the Expected Credit Loss, encapsulating the nuanced interplay of default probability, loss severity, and exposure magnitude into a single, comprehensive risk metric.

Carter is engineered to provide a seamless integration with existing financial infrastructures, facilitating real-time decision-making and ensuring scalability. Its modular architecture not only allows for individual core optimization but also enables parallel development and updates without systemic disruptions. Moreover, Carter is designed with regulatory compliance in mind, embedding the latest in financial regulations and risk management best practices to deliver not just insights, but actionable, compliant decision-making tools.

In essence, Carter aims to represent the pinnacle of credit risk assessment technology, offering unparalleled precision, adaptability, and insight, enabling financial institutions to make informed credit decisions with confidence.

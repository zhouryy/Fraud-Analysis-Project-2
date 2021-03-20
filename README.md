# Fraud-Analysis-Project-2

Supervised Fraud Classification on Application Data
- Start with a DQR
- Clean: treat the frivolous fields (SSN, Address, Phone, DOB)
- Create all variables
- Scale all variables (typically z scale)
- Separate data into modeling/Out of Time (OOT)
- Use the modeling data (trn,tst) for feature selection
- Select 20 – 30 best variables
- Build a baseline linear model (logistic regression)
- Build several nonlinear models, tune parameters (neural net, boosted trees (try a few different versions), random forest
- For each ML model, start with minimum complexity. Increase complexity until you observe overfitting
- Select your favorite model, fine tune the parameters
- Build the final performance tables with your final, best model
- Write report

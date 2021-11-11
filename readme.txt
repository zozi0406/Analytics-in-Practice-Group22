
1. Title: Credit Risk Prediction

2. Number of Instances: 31375 

3. Number of Attributes: 39

4. Attribute information:
	
  1) ID: client ID
  2) LIMIT: credit Limit of a client in dollars
  3) GENDER: 1 = male, 2 = female
  4) EDUCATION: (1=graduate school, 2=university, 3=high school, 0 = others, 4=others, 5=special program, 6=unknown)
  5) MARRIAGE: marital status (1=married, 2=single, 3=divorced, 0 = others)
  6) AGE: age in years
  7) AGE_CTG: age category (1= from 20 to 34; 2 = from 35 to 49; 3 = from 50 to 64; 4 = 65 and over)
  8 - 13) Variables PY1, PY2, PY3, PY4, PY5, PY6 : History of past payments. 
		 PY1 = the repayment status in period X; PY2 = the repayment status in period (X-1)
		 PY3 = the repayment status in period (X-2); PY4 = the repayment status in period (X-3)
		 PY5 = the repayment status in period (X-4); PY6 = the repayment status in period (X-5)
	
	Categories in these variables are:
	-2: No consumption/transaction;  -1: Paid in full;  0: small payment;  
	1 = payment delay for one period; 2 = payment delay for two periods; ...; 8 = payment delay for eight periods; 9 = payment delays for nine periods and above

  14 - 19) Variables = BILL1, BILL2, BILL3, BILL4, BILL5, BILL6: Amount of bill statement in dollars
		   BILL1: bill statement in period X; BILL2: bill statement in period (X-1)
		   BILL3: bill statement in period (X-2); BILL4: bill statement in period (X-3)
		   BILL5: bill statement in period (X-4); BILL6: bill statement in period (X-5)

  20 - 25) Variables: PYAMT1, PYAMT2, PYAMT3, PYAMT4, PYAMT5, PYAMT6: Amount of previous payment in dollars
		  PYAMT1: amount paid in period X; PYAMT2: amount paid in period (X-1)
		  PYAMT3: amount paid in period (X-2); PYAMT4: amount paid in period (X-3)
		  PYAMT5: amount paid in period (X-4); PYAMT6: amount paid in period (X-5)

  26) SATISFACTION: service satisfaction (0 = not satisfactory; 1= normal; 2 = satisfactory)
  27) FREQTRANSACTION: how frequently client visits Universal Plus (0 = rarely, 1 = regularly)
  28) PHONE: whether the client has a landline or not (0 = no phone; 1 = yes)
  29) DEPENDENT: whether the client has children or not (0 = no child; 1 = yes)
  30) CREDITCRD: number of credit cards
  31) RSTATUS: current accommodation status (0= shared lease, 1= homeowner,  2= rent)
  32) OTH_ACCOUNT: whether the client has several bank accounts (0= no, 1= yes)
  33) CAR: whether the client has a car (0 = no, 1 = yes)
  34) YEARSINADD: years in the current address (3 = three years or below, 4 = four years, ..., 7 = seven years or above)
  35) SECONDHOME: whether the client has another address (0 = no, 1 = yes)
  36) EMPLOYMENT: whether the client has a permenant job (0 = no, 1 = yes)
  37) NEW_CSTM: whether the client joined Universal Plus in the last two years or s/he is an existing customer (0 = joined in the last two years, 1 = existing customer)
  38) CM_HIST: criminal history, e.g. insurance fraud (0 = no, 1 = yes)
  39) CLASS: 0 = the client paid the credit back; 1 = the client did not pay the credit and went into default
  

Baseline:
The AUC score on the train set is: 0.7684320366883126
The AUC score on the valid set is: 0.7492316317568893
The AUC score on the test set is: 0.752255395862036
The stability score on the train set is: 0.5118108585063198
The stability score on the valid set is: 0.4609133480205614
The stability score on the test set is: 0.43951460419556865

RangeIndex: 915995 entries, 0 to 915994
Data columns (total 48 columns):
 #   Column                           Non-Null Count   Dtype   
---  ------                           --------------   -----   
 0   amtinstpaidbefduel24m_4187115A   579292 non-null  float64 
 1   annuity_780A                     915995 non-null  float64 
 2   annuitynextmonth_57A             915993 non-null  float64 
 3   avginstallast24m_3658937A        541370 non-null  float64 
 4   avglnamtstart24m_4525187A        97623 non-null   float64 
 5   avgoutstandbalancel6m_4187114A   411545 non-null  float64 
 6   avgpmtlast12m_4525200A           300125 non-null  float64 
 7   credamount_770A                  915995 non-null  float64 
 8   currdebt_22A                     915993 non-null  float64 
 9   currdebtcredtyperange_828A       915993 non-null  float64 
 10  disbursedcredamount_1113A        915995 non-null  float64 
 11  downpmt_116A                     915995 non-null  float64 
 12  inittransactionamount_650A       115562 non-null  float64 
 13  lastapprcommoditycat_1041M       915995 non-null  category
 14  lastapprcommoditytypec_5251766M  915995 non-null  category
 15  lastapprcredamount_781A          650910 non-null  float64 
 16  lastcancelreason_561M            915995 non-null  category
 17  lastotherinc_902A                1837 non-null    float64 
 18  lastotherlnsexpense_631A         1826 non-null    float64 
 19  lastrejectcommoditycat_161M      915995 non-null  category
 20  lastrejectcommodtypec_5251769M   915995 non-null  category
 21  lastrejectcredamount_222A        454384 non-null  float64 
 22  lastrejectreason_759M            915995 non-null  category
 23  lastrejectreasonclient_4145040M  915995 non-null  category
 24  maininc_215A                     609459 non-null  float64 
 25  maxannuity_159A                  732371 non-null  float64 
 26  maxannuity_4075009A              45573 non-null   float64 
 27  maxdebt4_972A                    732371 non-null  float64 
 28  maxinstallast24m_3658928A        541370 non-null  float64 
 29  maxlnamtstart6m_4525199A         296657 non-null  float64 
 30  maxoutstandbalancel12m_4187113A  456003 non-null  float64 
 31  maxpmtlast3m_4525190A            238607 non-null  float64 
 32  previouscontdistrict_112M        915995 non-null  category
 33  price_1097A                      782191 non-null  float64 
 34  sumoutstandtotal_3546847A        648957 non-null  float64 
 35  sumoutstandtotalest_4493215A     411707 non-null  float64 
 36  totaldebt_9A                     915993 non-null  float64 
 37  totalsettled_863A                915993 non-null  float64 
 38  totinstallast1m_4525188A         211726 non-null  float64 
 39  description_5085714M             900228 non-null  category
 40  education_1103M                  900228 non-null  category
 41  education_88M                    900228 non-null  category
 42  maritalst_385M                   900228 non-null  category
 43  maritalst_893M                   900228 non-null  category
 44  pmtaverage_3A                    85889 non-null   float64 
 45  pmtaverage_4527227A              69005 non-null   float64 
 46  pmtaverage_4955615A              43210 non-null   float64 
 47  pmtssum_45A                      343810 non-null  float64 
dtypes: category(13), float64(35)
memory usage: 258.6 MB

amtinstpaidbefduel24m_4187115A	Number of instalments paid before due date in the last 24 months.
annuity_780A	Monthly annuity amount.
annuitynextmonth_57A	Next month's amount of annuity.
avginstallast24m_3658937A	Average instalments paid by the client over the past 24 months.
avglnamtstart24m_4525187A	Average loan amount in the last 24 months.
avgoutstandbalancel6m_4187114A	Average outstanding balance of applicant for the last 6 months.
avgpmtlast12m_4525200A	Average of payments made by the client in the last 12 months.
credamount_770A	Loan amount or credit card limit.
currdebt_22A	Current debt amount of the client.
currdebtcredtyperange_828A	Current amount of debt of the applicant.
description_5085714M	Categorization of clients by credit bureau.
disbursedcredamount_1113A	Disbursed credit amount after consolidation.
downpmt_116A	Amount of downpayment.
education_1103M	Level of education of the client provided by external source.
education_88M	Education level of the client.
inittransactionamount_650A	Initial transaction amount of the credit application.
lastapprcommoditycat_1041M	Commodity category of the last loan applications made by the applicant.
lastapprcommoditytypec_5251766M	Commodity type of the last application.
lastapprcredamount_781A	Credit amount from the client's last application.
lastcancelreason_561M	Cancellation reason of the last application.
lastotherinc_902A	Amount of other income reported by the client in their last application.
lastotherlnsexpense_631A	Monthly expenses on other loans from the last application.
lastrejectcommoditycat_161M	Category of commodity in the applicant's last rejected application.
lastrejectcommodtypec_5251769M	Commodity type of the last rejected application.
lastrejectcredamount_222A	Credit amount on last rejected application.
lastrejectreason_759M	Reason for rejection on the most recent rejected application.
lastrejectreasonclient_4145040M	Reason for the client's last loan rejection.
maininc_215A	Client's primary income amount.
maritalst_385M	Marital status of the client.
maritalst_893M	Marital status of the client
maxannuity_159A	Maximum annuity previously obtained by client.
maxannuity_4075009A	Maximal annuity offered to the client in the current application.
maxdebt4_972A	Maximal principal debt of the client in the history older than 4 months.
maxinstallast24m_3658928A	Maximum instalment in the last 24 months
maxlnamtstart6m_4525199A	Maximum loan amount started in the last 6 months.
maxoutstandbalancel12m_4187113A	Maximum outstanding balance in the last 12 months.
maxpmtlast3m_4525190A	Maximum payment made by the client in the last 3 months.
pmtaverage_3A	Average of tax deductions.
pmtaverage_4527227A	Average of tax deductions.
pmtaverage_4955615A	Average of tax deductions.
pmtssum_45A	Sum of tax deductions for the client.
previouscontdistrict_112M	Contact district of the client's previous approved application.
price_1097A	Credit price.
sumoutstandtotal_3546847A	Sum of total outstanding amount.
sumoutstandtotalest_4493215A	Sum of total outstanding amount.
totaldebt_9A	Total amount of debt.
totalsettled_863A	Sum of all payments made by the client.
totinstallast1m_4525188A	Total amount of monthly instalments paid in the previous month.
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
 0   amtinstpaidbefduel24m_4187115A   579292 non-null  float64 Number of instalments paid before due date in the last 24 months.
 1   annuity_780A                     915995 non-null  float64 Monthly annuity amount.
 2   annuitynextmonth_57A             915993 non-null  float64 Next month's amount of annuity.
 3   avginstallast24m_3658937A        541370 non-null  float64 Average instalments paid by the client over the past 24 months.
 4   avglnamtstart24m_4525187A        97623 non-null   float64 Average loan amount in the last 24 months.
 5   avgoutstandbalancel6m_4187114A   411545 non-null  float64 Average outstanding balance of applicant for the last 6 months.
 6   avgpmtlast12m_4525200A           300125 non-null  float64 Average of payments made by the client in the last 12 months.
 7   credamount_770A                  915995 non-null  float64 Loan amount or credit card limit.
 8   currdebt_22A                     915993 non-null  float64 Current debt amount of the client.
 9   currdebtcredtyperange_828A       915993 non-null  float64 Current amount of debt of the applicant.
 10  disbursedcredamount_1113A        915995 non-null  float64 Disbursed credit amount after consolidation.
 11  downpmt_116A                     915995 non-null  float64 Amount of downpayment.
 12  inittransactionamount_650A       115562 non-null  float64 Initial transaction amount of the credit application.
 13  lastapprcommoditycat_1041M       915995 non-null  category Commodity category of the last loan applications made by the applicant.
 14  lastapprcommoditytypec_5251766M  915995 non-null  category Commodity type of the last application.
 15  lastapprcredamount_781A          650910 non-null  float64 Credit amount from the client's last application.
 16  lastcancelreason_561M            915995 non-null  category Cancellation reason of the last application.
 17  lastotherinc_902A                1837 non-null    float64 Amount of other income reported by the client in their last application.
 18  lastotherlnsexpense_631A         1826 non-null    float64 Monthly expenses on other loans from the last application.
 19  lastrejectcommoditycat_161M      915995 non-null  category Category of commodity in the applicant's last rejected application.
 20  lastrejectcommodtypec_5251769M   915995 non-null  category Commodity type of the last rejected application.
 21  lastrejectcredamount_222A        454384 non-null  float64 Credit amount on last rejected application.
 22  lastrejectreason_759M            915995 non-null  category Reason for rejection on the most recent rejected application.
 23  lastrejectreasonclient_4145040M  915995 non-null  category Reason for the client's last loan rejection.
 24  maininc_215A                     609459 non-null  float64 Client's primary income amount.
 25  maxannuity_159A                  732371 non-null  float64 Maximum annuity previously obtained by client.
 26  maxannuity_4075009A              45573 non-null   float64 Maximal annuity offered to the client in the current application.
 27  maxdebt4_972A                    732371 non-null  float64 Maximal principal debt of the client in the history older than 4 months.
 28  maxinstallast24m_3658928A        541370 non-null  float64 Maximum instalment in the last 24 months
 29  maxlnamtstart6m_4525199A         296657 non-null  float64 Maximum loan amount started in the last 6 months.
 30  maxoutstandbalancel12m_4187113A  456003 non-null  float64 Maximum outstanding balance in the last 12 months.
 31  maxpmtlast3m_4525190A            238607 non-null  float64 Maximum payment made by the client in the last 3 months.
 32  previouscontdistrict_112M        915995 non-null  category Contact district of the client's previous approved application.
 33  price_1097A                      782191 non-null  float64 Credit price.
 34  sumoutstandtotal_3546847A        648957 non-null  float64 Sum of total outstanding amount.
 35  sumoutstandtotalest_4493215A     411707 non-null  float64 Sum of total outstanding amount.
 36  totaldebt_9A                     915993 non-null  float64 Total amount of debt.
 37  totalsettled_863A                915993 non-null  float64 Sum of all payments made by the client.
 38  totinstallast1m_4525188A         211726 non-null  float64 Total amount of monthly instalments paid in the previous month.
 39  description_5085714M             900228 non-null  category Categorization of clients by credit bureau.
 40  education_1103M                  900228 non-null  category Level of education of the client provided by external source.
 41  education_88M                    900228 non-null  category Education level of the client.
 42  maritalst_385M                   900228 non-null  category Marital status of the client.
 43  maritalst_893M                   900228 non-null  category Marital status of the client
 44  pmtaverage_3A                    85889 non-null   float64 Average of tax deductions.
 45  pmtaverage_4527227A              69005 non-null   float64 Average of tax deductions.
 46  pmtaverage_4955615A              43210 non-null   float64 Average of tax deductions.
 47  pmtssum_45A                      343810 non-null  float64 Sum of tax deductions for the client.
dtypes: category(13), float64(35)
memory usage: 258.6 MB
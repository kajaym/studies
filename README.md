<!DOCTYPE html> 
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>SACCO</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400..800;1,400..800&display=swap" rel="stylesheet">
        <style type="text/css">
            @page {
                size: A4 potrait;
                margin: 0mm 0mm;
            }
            body {
                -webkit-print-color-adjust: exact;
                margin: 0px;
                padding: 0px; 
                font-family: "EB Garamond", serif;
                font-optical-sizing: auto;
                line-height: 145%;
            }
            p {
                margin: 0;
                text-align: left;
                padding: 0;
            }
            table {
                border-collapse: separate;
                border-spacing: 0;
                padding: 0;
                width: 100%;
                margin: 0;
                table-layout: auto;
            }
            td,
            th {
                padding: 0px;
                margin: 0;
            }
        </style>
    </head>
    <body style="height: fit-content;">
        <!-- Page 1 -->
        <div style="position: relative; background-color: #FFF;line-height: normal; page-break-after: always;">
            <table style="height: 100%;width: 100%;">
                <tr>
                    <td style="padding: 32px 32px; ">
                        <table style="border: 1px solid black;">
                            <!-- 1 -->
                            <tr>
                                <td style="padding: 24px 32px 0px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">FORM 1A</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;text-align: right;">(Reg. 5(2)                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- title -->
                            <tr>
                                <td style="vertical-align: top;padding: 4px 0px 32px;">
                                    <p style="font-size: 22px;font-weight: bold;text-align:center;">
                                        APPLICATION FOR AUTHORIZATION
                                     </p>
                                </td>
                            </tr>
                            <tr>
                                <td style="padding: 0px 32px;">
                                    <table>
                                        <!-- 1 -->
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">1.</p>
                                            </td>
                                            <td style="vertical-align: top; width: 32%;">
                                                <p style="font-size: 16px;font-weight: bold;">Name of SACCO Society:</p>
                                                <p style="font-size: 16px;font-weight: normal;">C.S. No:</p>
                                                <p style="font-size: 16px;font-weight: normal;">Date of Registration:</p>
                                            </td>
                                            <td style="vertical-align: top; ">
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.NameofSaccoSociety}}</p>
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.CSNumber}}</p>
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.DateofRegistration}}</p>
                                            </td>
                                        </tr>
                                        <!-- 2 -->
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;padding: 16px 0px;">
                                                <p style="font-size: 16px;font-weight: bold;">2.</p>
                                            </td>
                                            <td style="vertical-align: top; width: 32%;padding: 16px 0px;">
                                                <p style="font-size: 16px;font-weight: bold;">Location of Registered Office:</p>
                                            </td>
                                            <td style="vertical-align: top;padding: 16px 0px; ">
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.Building}}</p>
                                            </td>
                                        </tr>
                                        
                                    </table>
                                </td>
                            </tr>
                             <tr>
                                <td style="padding: 0px 32px;">
                                    <table>
                                        <!-- 3 -->
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">3.</p>
                                            </td>
                                            <td style="vertical-align: top; width: 44%;">
                                                <p style="font-size: 16px;font-weight: bold;">Physical Address of Head Office:<span style="font-weight: normal;"> L.R. No</span></p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.LRNumber}}</p>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;"></p>
                                            </td>
                                            <td style="vertical-align: top; padding-right: 28px;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 30%;">
                                                            <p style="font-size: 16px;font-weight: normal;">Street:</p>
                                                        </td>
                                                        <td style="width: 70%;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.Street}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; ">
                                                <table>
                                                    <tr>
                                                        <td style="width: 30%;">
                                                            <p style="font-size: 16px;font-weight: normal;">Building:</p>
                                                        </td>
                                                        <td style="width: 70%;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.Building}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                        </tr>
                                        <!-- 4 -->
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;padding-top: 20px;">
                                                <p style="font-size: 16px;font-weight: bold;">4.</p>
                                            </td>
                                            <td style="vertical-align: top; padding-right: 28px;padding-top: 20px;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 40%;vertical-align: top;">
                                                            <p style="font-size: 16px;font-weight: bold;">Postal Address:</p>
                                                        </td>
                                                        <td style="width: 60%;vertical-align: top;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.PostalAddress}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; padding-top: 20px;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 30%;">
                                                            <p style="font-size: 16px;font-weight: normal;">Postal Code:</p>
                                                        </td>
                                                        <td style="width: 70%;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.PostalCode}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                        </tr>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;"></p>
                                            </td>
                                            <td style="vertical-align: top; padding-right: 28px;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 40%;">
                                                            <p style="font-size: 16px;font-weight: normal;">Telephone No:</p>
                                                        </td>
                                                        <td style="width: 60%;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.TelephoneNumber}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; ">
                                                <table>
                                                    <tr>
                                                        <td style="width: 30%;">
                                                            <p style="font-size: 16px;font-weight: normal;">P.I.N NO:</p>
                                                        </td>
                                                        <td style="width: 70%;">
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.KRAPINNumber}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                             <!-- E-mail Address -->
                            <tr>
                                <td style="padding: 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;"></p>
                                            </td>
                                            <td style="vertical-align: top; width: 28%;">
                                                <p style="font-size: 16px;font-weight:normal;">E-mail Address:</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;text-align: center;">{{data.EmailAddress}}</p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- 5 -->
                            <tr>
                                <td style="padding: 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;padding: 16px 0px;">
                                                <p style="font-size: 16px;font-weight: bold;">5.</p>
                                            </td>
                                            <td style="vertical-align: top; padding: 16px 0px;">
                                                <p style="font-size: 16px;font-weight: bold;">Specified non-withdrawable deposit taking business the Sacco is engaged in;</p>
                                                <table>
                                                    <tr>
                                                        <td style="vertical-align: top; padding-left: 80px;padding-right: 16px;padding-top: 9px; width: 4%;">
                                                                {% if form_data.SpecifiednonwithdrawabledeposittakingbusinesstheSaccoisengagedin contains "Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million" %}
                                                                <input type="checkbox" name="Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million" id="Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million" checked>
                                                                {% else %}
                                                                <input type="checkbox" name="Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million" id="Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million">
                                                                {% endif %}
                                                        </td>
                                                        <td style="vertical-align: top;padding-top: 6px;">
                                                            <p style="font-size: 16px;font-weight: normal;">Non-withdrawable deposit taking Sacco business where members deposits equal to or exceed KShs 100 million </p>
                                                        </td>
                                                    </tr>
                                                    <tr>
                                                        <td style="vertical-align: top; padding-left: 80px;padding-right: 16px;padding-top: 9px; width: 4%;">
                                                            {% if form_data.SpecifiednonwithdrawabledeposittakingbusinesstheSaccoisengagedin contains "Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms" %}
                                                                <input type="checkbox" name="Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms" id="Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms" checked>
                                                                {% else %}
                                                                <input type="checkbox" name="Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms" id="Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms">
                                                                {% endif %}
                                                        </td>
                                                        <td style="vertical-align: top;padding-top: 6px;">
                                                            <p style="font-size: 16px;font-weight: normal;">Non-withdrawable deposits where registration and mobilization of share capital is through digital or other electronic payment platforms </p>
                                                        </td>
                                                    </tr>
                                                    <tr>
                                                        <td style="vertical-align: top; padding-left: 80px;padding-right: 16px;padding-top: 9px; width: 4%;">
                                                            {% if form_data.SpecifiednonwithdrawabledeposittakingbusinesstheSaccoisengagedin contains "Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country" %}
                                                                <input type="checkbox" name="Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country" id="Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country" checked>
                                                                {% else %}
                                                                <input type="checkbox" name="Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country" id="Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country">
                                                                {% endif %}
                                                        </td>
                                                        <td style="vertical-align: top;padding-top: 6px;">
                                                            <p style="font-size: 16px;font-weight: normal;">Non-withdrawable deposit taking Sacco business where deposits and shares mobilization is by persons ordinarily resident outside the country. </p>
                                                        </td>
                                                    </tr>
                                                </table>
                                                
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- 6 -->
                            <tr>
                                <td style="padding: 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">6.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    Names of places of business in Kenya and the number of years each has been established and has conducted or carried out business
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <tr>
                                <td style="padding:0px 32px; font-size: 16px;">
                                    <table style="border-bottom:1px solid black;">
                                        <tbody>
                                    
                                        <tr>
                                           <td style="width: 6%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td> 
                                           <td style="width: 18%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Name of Place of Business </p></td> 
                                           <td style="width: 32%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Name of Town, or Trading Centre or Market Centre where Branch is Located</p></td> 
                                           <td style="width: 27%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Country where branch is located</p></td> 
                                           <td style="width: 17%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Year of Establishment </p></td> 
                                        </tr>
                                            {% assign counter = 0 %}
                                             {% for item in data.NamesofplacesofbusinessinKenya %}
                                             {% assign counter = counter | plus: 1 %}
                                        
                                        <tr>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;"> {{counter}}.</td> 
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.NameofPlaceofBusiness}}</td>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.NameofTownorTradingCentreorMarketCentrewhereBranchisLocated}}</td> 
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Countywherebranchislocated}}</td>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.YearofEstablishment}}</td> 
                                         </tr>
                                         {% endfor %}
                                    </tbody>
                                </table>
                                </td>
                            </tr>
                              <!-- NB --> 
                            <tr>
                                <td style="vertical-align: top; padding-left: 80px;padding: 0px 32px 0px 80px;">
                                    <p style="font-size: 16px;font-weight: bold;font-style: italic;"><span style="border-bottom: 1px solid black;">
                                        NB: Attach to this application a list of other places of business. Provide name of the place of business, state whether it is a satellite, mobile unit etc.
                                    </span></p>
                                </td>
                            </tr>
                             <!-- 7 -->
                             <tr>
                                <td style="padding: 16px 32px 0px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">7.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    Former name(s), if applicable, by which the SACCO society has been known
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!--  -->
                            {% assign counter = 0 %}
                            {% for item in data.FormernamesifapplicablebywhichtheSACCOsocietyhasbeenknown %}
                            {% assign counter = counter | plus: 1 %}
                            <tr>
                                <td style="padding: 0px 32px 20px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; padding-left: 60px;width: 40%;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 8%;">
                                                            <p style="font-size: 16px;font-weight: normal;">{{counter}}.</p>
                                                        </td>
                                                        <td>
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;"> {{item.FormerName}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; ">
                                                <table>
                                                    <tr>
                                                        <td style="width: 18%;">
                                                            <p style="font-size: 16px;font-weight: normal;">from</p>
                                                        </td>
                                                        <td>
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;"> {{item.YearFrom}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; ">
                                                <table>
                                                    <tr>
                                                        <td style="width: 14%;">
                                                            <p style="font-size: 16px;font-weight: normal;">to</p>
                                                        </td>
                                                        <td>
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;"> {{item.YearTo}}</p>
                                                        </td>
                                                    </tr>
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            {% endfor %}
                             <!-- 8. -->
                             <tr>
                                <td style="padding: 16px 32px 0px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">8.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    Details of Capital
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <tr>
                                <td style="padding: 0px 32px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;width: 55%;">
                                                <table>
                                                    <tr>
                                                        <td style="width: 50%;">
                                                            <p style="font-size: 16px;font-weight: normal;">(a). Paid-up value(Equity)</p>
                                                        </td>
                                                        <td>
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;">Kshs. {{data.PaidupvalueEquity}}</p>
                                                        </td>
                                                    </tr>
                                                   
                                                </table>
                                            </td>
                                            <td style="vertical-align: top;padding-left: 28px; ">
                                                <table>
                                                    <tr>
                                                        <td style="width: 50%;">
                                                            <p style="font-size: 16px;font-weight: normal;">(b). Core capital</p>
                                                        </td>
                                                        <td>
                                                            <p style="font-size: 16px;font-weight: normal;border-bottom: 1px dashed black;"> Kshs. {{data.Corecapital}}</p>
                                                        </td>
                                                    </tr>
                                                    
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr> 
                            <!-- page number -->
                            <tr>
                                <td style="padding:4px 32px 12px;">
                                    <P style="text-align: right;font-size: 16px;border-top: 1px solid darkgray;padding-top: 4px;">1 <span style="padding: 0px 4px;">|</span> <span style="color: darkgray;">Page</span></P>
                                </td>
                            </tr>                  
                        </table>
                    </td>
                </tr>
            </table>
        </div>
        <!-- Page 2 -->
        <div style="position: relative; background-color: #FFF; page-break-after: always;">
            <table style="height: 100%;width: 100%;">
                <tr>
                    <td style="padding: 32px 32px; ">
                        <table style="border: 1px solid black;">
                            <tr>
                                <td style="padding: 20px 32px 8px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">FORM 1A</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;text-align: right;">(Reg. 5(2)                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- 9. -->
                            <tr>
                                <td style="padding: 16px 32px 16px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">9.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    List and types of the Subsidiary of the SACCO Society ((This section is <u>MANDATORY</u>)
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                             
                            <tr>
                                <td style="padding:8px 32px 0px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                        <tr>
                                           <td style="width: 4%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td> 
                                           <td style="width: 15%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Name of the Subsidiary</p></td> 
                                           <td style="width: 23%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Type of the subsidiary (Company or Co-  operative Housing, Investment etc.)</p></td> 
                                           <td style="width: 21%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Total SACCO Society’s shareholding in the Subsidiary</p></td> 
                                           <td style="width: 18%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Names Directors of the Subsidiary</p></td> 
                                           <td style="width: 18%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Director’s Position in the SACCO Society</p></td> 
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.ListandtypesoftheSubsidiaryoftheSACCOSociety %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>                                            
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}.</td> 
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.NameoftheSubsidiary}}</td>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Typeofthesubsidiary}}</td> 
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.TotalSACCOSocietysshareholdinginthesubsidiary}}</td>                                            
                                            <td style="vertical-align: top;  border-top: 1px solid black; border-right: 1px solid black;">
                                                <table style="border-bottom: 1px solid black;">
                                                    {% for item in item.DirectorsDetails %}
                                                    <tr>
                                                        <td style="padding: 12px 8px;border-top: 1px solid black;">{{item.NamesDirectorsoftheSubsidiary}}</td>
                                                    </tr>
                                                    <tr>
                                                        <td style="padding: 12px 8px;border-top: 1px solid black;">{{item.DirectorsPositionintheSACCOSociety}}</td>
                                                    </tr>
                                                    {% endfor %}
                                                </table>
                                            </td> 
                                            <td style="vertical-align: top;border-top: 1px solid black; border-right: 1px solid black;">
                                                <table style="border-bottom: 1px solid black;">
                                                    {% for item in item.DirectorsDetails %}
                                                    <tr>
                                                        <td style="padding: 12px 8px;border-top: 1px solid black;">{{item.DirectorsPositionintheSACCOSociety}}</td>
                                                    </tr>
                                                    {% endfor %}
                                                </table>
                                            </td>
                                         </tr>
                                         {% endfor %}                                         
                                    </tbody>
                                </table>
                                </td>
                            </tr>
                            <!-- 10 -->
                            <tr>
                                <td style="padding: 16px 32px 16px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">10.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    Particulars of Officers, Officials and Office Bearers (This section is <u>MANDATORY</u>):
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                             <!-- a) -->
                            <tr>
                                <td style="padding: 8px 32px 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">a)</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    <strong>Directors</strong><br>
                                                    List the Full Names of all the Directors, officials or office bearers of the SACCO Society including the date they assumed office; gender and year of Birth.
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:8px 32px 24px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="8" style="vertical-align: top; padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF DIRECTORS, OFFICIALS AND OFFICE BEARS OF THE SACCO SOCIETY</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 4%;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td>
                                           <td style="vertical-align: top; width: 29%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Full Names of the Directors</p></td> 
                                           <td style="vertical-align: top; width: 10%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Designation</p></td> 
                                           <td style="vertical-align: top; width: 9%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Date of Assumption of office as Director</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Gender i.e. Male or Female</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Year of Birth </p></td>
                                           <td style="vertical-align: top; width: 20%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Current Place or Institution of work or employer of Director; or place and nature of business </p></td>
                                           <td style="vertical-align: top; width: 12%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Personal Telephone Number of Directors </p></td>
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.Directors %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}.</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.FullNamesoftheDirector}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Designation}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.DateofAssumptionofofficeasDirector}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Gender}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.YearofBirth}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.CurrentPlaceorInstitutionofworkoremployerofDirectororplaceandnatureofbusiness}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.PersonalTelephoneNumberofDirectors}}</td>                                              
                                         </tr>
                                         {% endfor %}                                                                                                                                                                                                             
                                    </tbody>
                                </table>
                                </td>
                            </tr> 
                            <!-- page number -->
                            <tr>
                                <td style="padding:4px 32px 12px;">
                                    <P style="text-align: right;font-size: 16px;border-top: 1px solid darkgray;padding-top: 4px;">2 <span style="padding: 0px 4px;">|</span> <span style="color: darkgray;">Page</span></P>
                                </td>
                            </tr>                  
                        </table>
                    </td>
                </tr>
            </table>
        </div>
         <!-- Page 3 -->
         <div style="position: relative; background-color: #FFF; page-break-after: always;">
            <table style="height: 100%;width: 100%;">
                <tr>
                    <td style="padding: 30px 32px; ">
                        <table style="border: 1px solid black;">
                            <tr>
                                <td style="padding: 12px 32px 8px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">FORM 1A</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;text-align: right;">(Reg. 5(2)                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                             <!-- b) -->
                            <tr>
                                <td style="padding: 8px 32px 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">b)</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    <strong>Supervisory Committee</strong><br>
                                                    List the Full Names of all the members of the Supervisory Committee of the SACCO Society including the date they assumed office; gender and year of Birth
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:4px 32px 4px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="8" style="vertical-align: top;  padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF MEMBERS OF SUPERVISORY COMMITTEE OF THE SACCO SOCIETY</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 4%;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td>
                                           <td style="vertical-align: top; width: 29%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Full Names of the Directors</p></td> 
                                           <td style="vertical-align: top; width: 10%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Designation</p></td> 
                                           <td style="vertical-align: top; width: 9%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Date of Assumption of office as Director</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Gender i.e. Male or Female</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Year of Birth </p></td>
                                           <td style="vertical-align: top; width: 20%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Current Place or Institution of work or employer of Director; or place and nature of business </p></td>
                                           <td style="vertical-align: top; width: 12%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Personal Telephone Number of Directors </p></td>
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.SupervisoryCommittee %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}.</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.FullNames}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Designation}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.DateofAssumptionofofficeasDirector}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Gender}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.YearofBirth}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.CurrentPlaceorInstitutionofworkoremployerofDirectororplaceandnatureofbusiness}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.PersonalTelephoneNumberofDirectors}}</td> 
                                         </tr>
                                         {% endfor %}
                                        </tbody>                                                                                                                         
                                </table>
                                </td>
                            </tr>     
                            <!-- c) -->
                            <tr>
                                <td style="padding: 4px 32px 4px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">c)</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    <strong>Senior Management (This section is <u>MANDATORY</u>).</strong><br>
                                                    List the particulars of ALL Senior Management Officers in the SACCO Society clearly stating their designations; Highest Academic qualification, Professional Qualifications and Date of Appointment to current position in the table below.
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:4px 32px 4px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="9" style="vertical-align: top;  padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF SENIOR MANAGEMENT AND OFFICERS OF THE SACCO SOCIETY</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 4%;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td>
                                           <td style="vertical-align: top; width: 26%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Full Names of the Officer</p></td> 
                                           <td style="vertical-align: top; width: 10%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Designation</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Date of Appointment to Current Position</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Gender i.e. Male or Female</p></td> 
                                           <td style="vertical-align: top; width: 8%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Year of Birth </p></td>
                                           <td style="vertical-align: top; width: 14%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Highest Academic Qualifications (e.g. Bachelors, or Masters or Diploma Certificate etc.)</p></td> 
                                           <td style="vertical-align: top; width: 11%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Professional Qualifications (e.g. CPS, CPA, Advocate etc.)</p></td>
                                           <td style="vertical-align: top; width: 11%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Personal Telephone Number of Directors</p></td>
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.SeniorManagement %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.FullNamesoftheOfficer}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Designation}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.DateofAppointmenttoCurrentPosition}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Gender}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.YearofBirth}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.HighestAcademicQualifications}} {{item.Specialisation}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.ProfessionalQualifications}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.PersonalTelephoneNumber}}</td> 
                                         </tr>
                                         {% endfor %}                                                                                                                                                                    
                                    </tbody>
                                </table>
                                </td>
                            </tr> 
                            <!-- d) -->
                            <tr>
                                <td style="vertical-align: top; padding: 8px 32px 8px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">d)</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    <strong>Former Senior Management who left the service of the Sacco Society in the last twelve (12) Months (This section is <u>MANDATORY</u>).
                                                    </strong><br>
                                                    List the names of the former Senior Management Officers who left or quit the service of the SACCO Society in the last twelve (12) months and the reasons for leaving the service of the Sacco Society.
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:8px 32px 8px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="9" style="vertical-align: top; padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF SENIOR MANAGEMENT AND OFFICERS OF THE SACCO SOCIETY</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 4%;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td>
                                           <td style="vertical-align: top; width: 18%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Full Names of the Officer</p></td> 
                                           <td style="vertical-align: top; width: 13%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Immediate Former Designation at exit</p></td> 
                                           <td style="vertical-align: top; width: 10%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Gender i.e. Male or Female</p></td> 
                                           <td style="vertical-align: top; width: 13%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Last Date of employment with the SACCO</p></td>
                                           <td style="vertical-align: top; width: 42%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Brief reason for the Officers exit from the service of the SACCO Society e.g. contract expired, retired, resigned, dismissed etc.</p></td> 
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.FormerSeniorManagement %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}.</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.FullNamesoftheOfficer}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.ImmediateFormerDesignationatexit}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.Gender}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.LastDateofemploymentwiththeSACCO}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.BriefreasonfortheOfficersexitfromtheserviceoftheSACCOSociety}}</td> 
                                        </tr>
                                        {% endfor %}                                                                                  
                                    </tbody>
                                </table>
                                </td>
                            </tr> 
                            <!-- page number -->
                            <tr>
                                <td style="padding:4px 32px 12px;">
                                    <P style="text-align: right;font-size: 16px;border-top: 1px solid darkgray;padding-top: 4px;">3 <span style="padding: 0px 4px;">|</span> <span style="color: darkgray;">Page</span></P>
                                </td>
                            </tr>                  
                        </table>
                    </td>
                </tr>
            </table>
        </div>
        <!-- Page 4 -->
        <div style="position: relative; background-color: #FFF;">
            <table style="height: 100%;width: 100%;">
                <tr>
                    <td style="padding: 32px 32px; ">
                        <table style="border: 1px solid black;">
                            <tr>
                                <td style="padding: 20px 32px 8px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">FORM 1A</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;text-align: right;">(Reg. 5(2)                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- 11 -->
                            <tr>
                                <td style="padding: 8px 32px 0px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">11.</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    <strong>
                                                        Particulars of external auditors of the SACCO Society for current year
                                                    </strong><br>
                                                    List the particular details of the external auditors of the SACCO Society for the current financial period in the following table;
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:8px 32px 24px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="4" style="vertical-align: top; padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF THE EXTERNAL AUDITORS OF THE CURRENT YEAR</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 25%; vertical-align: top; padding: 1px 6px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Full Names of the External Auditors of the SACCO Society</p></td>
                                           <td style="vertical-align: top; width: 25%; vertical-align: top; padding: 1px 6px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Postal and Physical Address or Location of the offices of External Auditor</p></td> 
                                           <td style="vertical-align: top; width: 25%; vertical-align: top; padding: 1px 6px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Number of Partners in the External Audit Firm</p></td> 
                                           <td style="vertical-align: top; width: 25%; vertical-align: top; padding: 1px 6px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Telephone Number of the External Auditor</p></td> 
                                        </tr>                                        
                                        {% for item in data.Particularsofexternalauditors %}
                                        <tr>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-bottom: 1px solid black;  border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{item.FullNamesoftheExternalAuditorsoftheSACCOSociety}}</td> 
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-bottom: 1px solid black; border-right: 1px solid black;">{{item.LocationoftheofficesofExternalAuditor}}</td>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-bottom: 1px solid black; border-right: 1px solid black;">{{item.NumberofPartnersintheExternalAuditFirm}}</td>
                                            <td style="vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-bottom: 1px solid black; border-right: 1px solid black;">{{item.TelephoneNumberAuditor}}</td> 
                                        </tr>
                                        {% endfor %}
                                    </tbody>
                                </table>
                                </td>
                            </tr>  
                            <!-- 12 -->
                            <tr>
                                <td style="padding: 16px 32px 16px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">12</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">
                                                    Names of Bankers and their Address (This section is <u>MANDATORY</u>) Provide the particulars of ALL the SACCO Society’s Bankers.
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                             </tr>
                            <tr>
                                <td style="vertical-align: top; padding:8px 32px 24px 32px; font-size: 17px;">
                                    <table style="border-bottom: 1px solid black;">
                                        <tbody>
                                            <tr>
                                                <td colspan="5" style="vertical-align: top; padding: 1px 8px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">PARTICULARS OF BANKERS AND BANK ACCOUNTS OF THE SACCO SOCIETY</p></td>
                                             </tr>
                                        <tr>
                                           <td style="vertical-align: top; width: 4%;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">No.</p></td>
                                           <td style="vertical-align: top; width: 30%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Bank Name</p></td> 
                                           <td style="vertical-align: top; width: 21%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Branch Name</p></td> 
                                           <td style="vertical-align: top; width: 20%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Account Number(s)</p></td> 
                                           <td style="vertical-align: top; width: 25%; vertical-align: top; padding: 1px 4px; border-top: 1px solid black;border-right: 1px solid black;"><p style="font-weight: bold;">Nature of Account e.g. overdraft, current, settlement etc.</p></td>
                                        </tr>
                                        {% assign counter = 0 %}
                                        {% for item in data.ParticularsofBankers %}
                                        {% assign counter = counter | plus: 1 %}
                                        <tr>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-left: 1px solid black;border-right: 1px solid black;font-weight: bold;">{{counter}}.</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.BankName}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.BranchName}}</td> 
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.AccountNumber}}</td>
                                            <td style="vertical-align: top;  padding: 1px 4px; border-top: 1px solid black; border-right: 1px solid black;">{{item.NatureofAccount}}</td>
                                        </tr>
                                        {% endfor %}                                                                                 
                                    </tbody>
                                </table>
                                </td>
                            </tr> 
                            <!-- 13 -->
                            <tr>
                                <td style="padding: 8px 32px 12px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">13</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    Has the SACCO Society ever been put under receivership or made any compromise or arrangement with its creditors or otherwise failed to satisfy creditors in full?
                                                    <span style="border-bottom: 1px dashed black; padding: 0px 40px;font-weight: bold;">{{data.HastheSACCOSocietyeverbeenputunderreceivershipormadeanycompromiseorarrangementwithitscreditorsorotherwisefailedtosatisfycreditorsinfull}}</span>
                                                </p>
                                                <table>
                                                    <td style="vertical-align: top;">
                                                        <table>
                                                            <tbody>
                                                                <tr>
                                                                    {% if data.HastheSACCOSocietyeverbeenputunderreceivershipormadeanycompromiseorarrangementwithitscreditorsorotherwisefailedtosatisfycreditorsinfull == "Yes" %}
                                                                <td style="vertical-align: top;width: 30%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">If so, give particulars</p>
                                                                </td>
                                                                <td style="vertical-align: top;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">{{data.Ifsogiveparticulars1}}</p>
                                                                </td>
                                                                {% endif %}
                                                            </tr>
                                                        </tbody></table>
                                                    </td>
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- 14 -->
                            <tr>
                                <td style="padding: 12px 32px 12px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">14</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    Is the SACCO Society under investigation by an inspector or other authorized officer of any government ministry, department or agency, professional association or other regulatory body or has any investigation ever taken place in the   affairs of  the SACCO   society
                                                    <span style="border-bottom: 1px dashed black; padding: 0px 40px;font-weight: bold;">{{data.IstheSACCOSocietyunderinvestigationbyaninspectororotherauthorizedofficerofanygovernmentministrydepartmentoragencyprofessionalassociationorotherregulatorybodyorhasanyinvestigationevertakenplaceintheaffairsoftheSACCOsociety}}</span>
                                                </p>
                                                <table>
                                                    <td style="vertical-align: top;">
                                                        <table>
                                                            <tbody><tr>
                                                                {% if data.IstheSACCOSocietyunderinvestigationbyaninspectororotherauthorizedofficerofanygovernmentministrydepartmentoragencyprofessionalassociationorotherregulatorybodyorhasanyinvestigationevertakenplaceintheaffairsoftheSACCOsociety == "Yes" %}
                                                                <td style="vertical-align: top;width: 30%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">If so, give particulars </p>
                                                                </td>
                                                                <td style="vertical-align: top;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">{{data.Ifsogiveparticulars2}}</p>
                                                                </td>
                                                                {% endif %}
                                                            </tr>
                                                        </tbody></table>
                                                    </td>
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr> 
                            <!-- 15 -->
                            <tr>
                                <td style="padding: 12px 32px 8px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;">15</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: normal;">
                                                    15. Is the SACCO Society currently engaged or does it expect to be involved in any litigation which may have a material effect on the resources of the SACCO Society?
                                                    <span style="border-bottom: 1px dashed black; padding: 0px 40px;font-weight: bold;">{{data.IstheSACCOSocietycurrentlyengagedordoesitexpecttobeinvolvedinanylitigationwhichmayhaveamaterialeffectontheresourcesoftheSACCOSociety}}</span>
                                                </p>
                                                <table>
                                                    <td style="vertical-align: top;">
                                                        <table>
                                                            <tbody><tr>
                                                                {% if data.IstheSACCOSocietycurrentlyengagedordoesitexpecttobeinvolvedinanylitigationwhichmayhaveamaterialeffectontheresourcesoftheSACCOSociety == "Yes" %}
                                                                <td style="vertical-align: top;width: 30%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">If so, give particulars </p>
                                                                </td>
                                                                <td style="vertical-align: top;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">{{data.Ifsogiveparticulars3}}</p>
                                                                </td>
                                                                {% endif %}
                                                            </tr>
                                                        </tbody></table>
                                                    </td>
                                                </table>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- page number -->
                            <tr>
                                <td style="padding:20px 32px 12px;">
                                    <P style="text-align: right;font-size: 16px;border-top: 1px solid darkgray;padding-top: 4px;">4 <span style="padding: 0px 4px;">|</span> <span style="color: darkgray;">Page</span></P>
                                </td>
                            </tr>                  
                        </table>
                    </td>
                </tr>
            </table>
        </div>
         <!-- Page 5 -->
         <div style="position: relative; background-color: #FFF; page-break-after: always;">
            <table style="height: 100%;width: 100%;">
                <tr>
                    <td style="padding: 32px 32px; ">
                        <table style="border: 1px solid black;line-height: normal;">
                            <tr>
                                <td style="padding: 20px 32px 8px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;">FORM 1A</p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;text-align: right;">(Reg. 5(2)                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <tr>
                                <td style="padding: 12px 32px 20px 32px;">
                                    <table>
                                        <tr>
                                            <td style="vertical-align: top; width: 4%;">
                                                <p style="font-size: 16px;font-weight: bold;"></p>
                                            </td>
                                            <td style="vertical-align: top;">
                                                <p style="font-size: 16px;font-weight: bold;padding-bottom: 12px;">
                                                    <span style="border-bottom: 1px solid black;">DECLARATION</span><br>
                                                </p>
                                                <p style="font-size: 16px;font-weight: normal;padding-bottom: 12px;">
                                                    <input type="checkbox" name="studentdeclaration" id="studentdeclaration" checked>
                                                    {{data.Declaration2}}
                                                </p>
                                                <p style="font-size: 16px;font-weight: bold;">a) Chairman</p>
                                                <table>
                                                    <td style="padding-bottom: 20px;">
                                                        <table>
                                                            <tbody>
                                                            <tr>
                                                                <td style="vertical-align: top;width: 16%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">(Name): </p>
                                                                </td>
                                                                <td colspan="3" style="vertical-align: top;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td style="vertical-align: top;width: 16%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">Signature: </p>
                                                                </td>
                                                                <td style="vertical-align: top;padding-right: 60px;width: 30%;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                                <td style="vertical-align: top;width: 12%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">Date: </p>
                                                                </td>
                                                                <td style="vertical-align: top;width: 42%;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                            </tr>
                                                            </tbody>
                                                        </table>
                                                    </td>
                                                </table>
                                                <p style="font-size: 16px;font-weight: bold;">b) Chief Executive Officer</p>
                                                <table>
                                                    <td style="padding-bottom: 20px;">
                                                        <table>
                                                            <tbody>
                                                            <tr>
                                                                <td style="vertical-align: top;width: 16%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">(Name): </p>
                                                                </td>
                                                                <td colspan="3" style="vertical-align: top;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                            </tr>
                                                            <tr>
                                                                <td style="vertical-align: top;width: 16%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">Signature: </p>
                                                                </td>
                                                                <td style="vertical-align: top;padding-right: 60px;width: 30%;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                                <td style="vertical-align: top;width: 12%;">
                                                                    <p style=" font-size: 16px;font-weight: normal;">Date: </p>
                                                                </td>
                                                                <td style="vertical-align: top;width: 42%;">
                                                                    <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                                </td>
                                                            </tr>
                                                            </tbody>
                                                        </table>
                                                    </td>
                                                </table>
                                                <p style="font-size: 16px;font-weight: normal;padding-top: 32px;">
                                                    <span style="border-bottom: 1px solid black;font-weight: bold;">DECLARED AND WITNESSED BEFORE ME:</span>
                                                </p>
                                                <table>
                                                    <td style="vertical-align: top;width: 50%;padding-top: 12px;">
                                                        <p style="font-size: 16px; border-bottom: 1px dashed black;font-weight: bold;">&nbsp;</p>
                                                    </td>
                                                    <td style="width: 50%;">&nbsp;</td>
                                                </table>
                                                <p style="font-size: 16px;font-weight: bold;padding-top: 32px;">COMMISSIONER FOR OATHS/MAGISTRATE</p>
                                                <table>
                                                    <!-- date -->
                                                    <tr>
                                                        <td style="font-size: 16px;padding: 20px 0px;">
                                                            <table>
                                                                <tr>
                                                                    <td>
                                                                        <table>
                                                                            <tbody>
                                                                                <tr>
                                                                                    <td style="vertical-align: top;">
                                                                                        <p style="font-weight: bold;">THIS: <span style="border-bottom:1px dashed black;">&nbsp;</span></p>
                                                                                    </td>
                                                                                    <td style="vertical-align: top;">
                                                                                        <p style="font-weight: bold;">DAY OF: <span style="border-bottom:1px dashed black;">&nbsp;</span></p>
                                                                                    </td>
                                                                                    <td style="vertical-align: top;">
                                                                                        <p style="font-weight: bold;">20<span style="border-bottom:1px dashed black;">&nbsp;</span></p>
                                                                                    </td>
                                                                                </tr>
                                                                            </tbody>
                                                                        </table>
                                                                    </td>
                                                                    <td style="width: 50%;">&nbsp;</td>
                                                                </tr>
                                                            </table>
                                                        </td>
                                                    </tr>
                                                </table>
                                                 <!-- NB --> 
                                                <p style="font-size: 16px;font-weight: bold;font-style: italic;padding-left:60px ;padding-top: 20px;line-height: normal; "><span style="border-bottom: 1px solid black;">Notes:</span><br>
                                                    This application must be accompanied by all the relevant documents and requirements prescribed in the Act and these Regulations. It must be declared and witnessed before a Commissioner for Oaths or Magistrate to verify the correctness, accuracy and veracity of the disclosures therein
                                                </p>
                                            </td>
                                        </tr>
                                    </table>
                                </td>
                            </tr>
                            <!-- page number -->
                            <tr>
                                <td style="padding:400px 32px 12px;">
                                    <P style="text-align: right;font-size: 16px;border-top: 1px solid darkgray;padding-top: 4px;">5 <span style="padding: 0px 4px;">|</span> <span style="color: darkgray;">Page</span></P>
                                </td>
                            </tr>  
                        </table>
                    </td>
                </tr>
            </table>
        </div>
    </body>
</html>

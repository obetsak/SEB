// ==UserScript==
// @name       Swith from and to Account at SEB
// @namespace  kastebo.com
// @version    0.1
// @description  Switches the inputs for account to transfer from and to for both PG/BG and Account transfer
// @match      https://privat.ib.seb.se/wow/*
// @copyright  2015+, Jonas Kastebo
// @grant      none
// ==/UserScript==


    var toAccount = $('#IKPMaster_MainPlaceHolder_updPaymentAccount').closest('.control-group');
    var fromAccount = $('#IKPMaster_MainPlaceHolder_A1').closest('.control-group');

    toAccount.insertBefore(fromAccount);

    var toAccount = $('#IKPMaster_MainPlaceHolder_updTransferAccount').closest('.control-group');
    var fromAccount = $('#IKPMaster_MainPlaceHolder_A7').closest('.control-group');

    toAccount.insertBefore(fromAccount);

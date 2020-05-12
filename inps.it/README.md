I decided to save the page in a personal repository the epic fail that INPS have done.

I am sorry for anyone who is not italian that will not understand the meaning of the variables because those have been written (ofc) in italian, but I believe the level of the code is pretty much self explaining.

I would lik to remark couple of lines that are completely insane:

    function () {
                        ResizeSmart();
                        var chiave = 'true';
                        if (chiave.toLowerCase() == 'true')
                            if (leggiCookie('newSCCSB') == '') {
Well, INPS, what the actual fuck?! But let's continue...

    function aggiungiZero(iNumero)
    {
    	var asd = iNumero;
    	if (asd < 10)
    	{
    		return "0" + iNumero;
    	}
    	else
    	{
    		return iNumero;
    	}
    }
	
So cute. And last, but not least, why don't keep debug alerts because "just in case"?

    function ResizeSmart() { 
    	if ($(window).width() < 1100) 
    	{
    	// alert($(window).height());                                                
    	$("#objNewcerca").css("display", "none");
		
LOVELY!

![WTF](https://i.ibb.co/BsW2nHG/wtf.png)
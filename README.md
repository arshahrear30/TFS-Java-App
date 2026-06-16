NeumorphCardView startbutton=findViewById(R.id.start);
startbutton.setOnClickListener(new View.OnClickListener() {
   @Override
   public void onClick(View v) {
       Intent startbutton=new Intent(MainActivity.this,MainActivity2.class);
       startActivity(startbutton);
   }
});





বাটন টাইপ একটা নতুন নাম দিব=fiলিখলে findViewById()আসবে । তারপর () মাঝে R.id লিখবো আবার ডট দিবো তারপর id যেটা set করছিলাম xml file এ ঐটা লিখবো ।  
নতুন নাম ডট setOnClickListener( এবার new টাইফ করে blank দিলে recomendation আসবে। View.OnClickListener এ  চাপ দিবো ।
Intent লিখবো তারপর নতুন নাম =N লিখলে recomendation আসবে ।new Intent()চাপ দিবো । click button যে activity তে আছে তার নাম ডট this কমা, নতুন activity page name ডট class । এরপর; সেমিকোলন দিয়ে নিচের লাইনে startActivity(নতুন নাম)সেমিকোলন









Page Connection:

Button Class6;
Class6=findViewById(R.id.class6);
Class6.setOnClickListener(new View.OnClickListener() {	
           @Override
	public void onClick(View v) {
    	Intent Class6= new Intent(MainActivity.this, MainActivity2.class);
    	startActivity(Class6);
	}
});


implementation("com.github.fornewid:neumorphism:0.3.2")
jcenter() 
maven { url = uri(  "https://jitpack.io" )}

Button এর backend এ কাজ : 

TextView tvcountid; 
int count;// count নামে variable ধরলাম
Onclick এর ভিতরে 
count++;//
tvcountid.setText(""+count);


Toast:
Toast.makeText(MainActivity.this,"Wright here",Toast.LENGTH_SHORT ).show();


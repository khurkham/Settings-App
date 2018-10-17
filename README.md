# Settings-App

protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_font_oppo3);


        //Setting Display Change Font
        // Button displayBtn = (Button) findViewById(R.id.FontOppo2);
        // displayBtn .setOnClickListener(new View.OnClickListener() {
        //    public void onClick(View v) {
        //        startActivity(new Intent(Settings.ACTION_DISPLAY_SETTINGS));
        //    }
        // });


        Button APPLICATION = (Button) findViewById(R.id.FontOppo3);
        APPLICATION.setOnClickListener(new View.OnClickListener() {
            public void onClick(View v) {


                //တူၺ်းၽႅၵ်ႉၵဵတ်ႇဢႅပ်ႉ
                //Intent intent = new Intent();
               // intent.setAction(Settings.ACTION_APPLICATION_DETAILS_SETTINGS);
                // Uri uri = Uri.fromParts("package",getPackageName(), null);
              // intent.setData(uri);
               // startActivity(intent);
               
               //တူၺ်ၽႅၵ်ႉၵဵတ်ႇတၢင်ႇဢၼ်

                startActivity(new Intent(android.provider.Settings.ACTION_APPLICATION_DETAILS_SETTINGS, Uri.parse("package:com.nearme.themespace")));


                //တီႈလႆၢႈၾွၼ်ႉ
                //Intent intent  = new Intent(Settings.ACTION_DISPLAY_SETTINGS);
                //startActivityForResult(intent, 0);

                               //ဢႅပ်ႉဢၼ်တိတ်းတင်ႈယဝ်ႉ
               // Intent intent  = new Intent(Settings.ACTION_MANAGE_APPLICATIONS_SETTINGS);
               // startActivityForResult(intent, 0);



                //ဢႅပ်ႉဢၼ်တိတ်းတင်ႈယဝ်ႉ
               // Intent intent  = new Intent(Settings.ACTION_MANAGE_APPLICATIONS_SETTINGS);
               // startActivityForResult(intent, 0);



                //တႃႉေတလိူၵ်ႈၶဝ်ႈဢႅပ်ႉ
                //Intent intent  = new Intent(Settings.ACTION_INTERNAL_STORAGE_SETTINGS);
               //startActivityForResult(intent, 0);


            }


        });
        
        
        လဵပ်ႈႁဵၼ်းလႆႈတီႈၼႆႈထႅင်ႈ 
        https://developer.android.com/reference/android/provider/Settings#ACTION_APPLICATION_DETAILS_SETTINGS




       







    }

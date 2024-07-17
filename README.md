













## progressDialog 



   ```bash


     public class registration extends AppCompatActivity {

         android.app.ProgressDialog progressDialog;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_registration);




        //PrograsDialog
        progressDialog = new ProgressDialog(this);
        progressDialog.setMessage("Please Wait...");
        progressDialog.setCancelable(false);

        }

   ```

  ## Show progressDialog 



   ```bash


     progressDialog.show();


   ```

   ## Hide progressDialog 



   ```bash

         progressDialog.dismiss();

   ```

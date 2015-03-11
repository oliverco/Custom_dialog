Sample code:

                Runnable sampleFunction = new Runnable() {
                    @Override
                    public void run() {
                        // TODO Auto-generated
                        Toast.makeText(MainActivity.this,"click",Toast.LENGTH_SHORT).show();
                    }
                };
                new CustomDialog(MainActivity.this
                        , "Delete", "Are you sure you want to delete?", null, null, true).show();

//new CustomDialog(context,title,message,runnable for positive, runnable for negative, ok button).show();
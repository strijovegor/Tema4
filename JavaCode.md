```java
public class GymAdapter extends RecyclerView.Adapter<GymAdapter.GymViewHolder> {
    ArrayList<Gym> gyms;

    public GymAdapter (ArrayList<Gym> gyms){
        this.gyms = gyms;
    }
    public class GymViewHolder extends RecyclerView.ViewHolder{
        EditText edtV;
        EditText edtC;
        TextView desc;

        public GymViewHolder (View view){
            super(view);

            edtV = (EditText) view.findViewById(R.id.edtV);
            edtC = (EditText) view.findViewById(R.id.edtC);
            desc = (TextView) view.findViewById(R.id.desc);

        }
    }

```

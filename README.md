# MOONnaomi
JAWABAN UAS NOMER 3
public class minimarket {
    private String M_Id;
    private String M_name;
    private String M_store;
    private String M_nik;
    private String M_owner_name;
    private String M_xpathfactory coordinates = xpathfactory.newinstance();
    private String M_joindate;
    private boolean M_star;
    private ArrayList<itembelanja> itemsell;

    public String getM_Id(){
        return R_id;
    }

    public void setM_Id(String m_Id) {
        M_Id = m_Id;
    }

    public String getM_name() {
        return M_name;
    }

    public void setM_name(String m_name) {
        M_name = m_name;
    }

    public String getM_store() {
        return M_store;
    }

    public void setM_store(String m_store) {
        M_store = m_store;
    }

    public String getM_nik() {
        return M_nik;
    }

    public void setM_nik(String m_nik) {
        M_nik = m_nik;
    }

    public String getM_owner_name() {
        return M_owner_name;
    }

    public void setM_owner_name(String m_owner_name) {
        M_owner_name = m_owner_name;
    }

    public String getM_xpathfactory() {
        return M_xpathfactory;
    }

    public void setM_xpathfactory(String m_xpathfactory) {
        M_xpathfactory = m_xpathfactory;
    }

    public String getM_joindate() {
        return M_joindate;
    }

    public void setM_joindate(String m_joindate) {
        M_joindate = m_joindate;
    }
    public boolean isM_star(){
        return M_star
    }

    public ArrayList<itembelanja> getItemsell() {
        return itemsell;
    }

    public void setItemsell(ArrayList<itembelanja> itemsell) {
        this.itemsell = itemsell;
    }

    public Arraylist<minimarket>Finditem(String findText){
        Arraylist<minimarket> findArray = new ArrayList<>();
        for (int index=0;index<itemsell.size();index ++){
            minimarket toFind = new minimarket();
            Scanner sc = new Scanner (System.in);
            System.out.println("face wash= ");
            s.setNamaBarang (sc.nextLine());
            System.out.println("8.000*3000= ");
            s.setHargabarang(sc.nextInt());
            System.out.println("typeQty");
            sc.setjumlahbelanja(sc.nextInt());
            p.add(s);
        }
        return findArray;

        System.out.println("===========================");
        System.out.format("total belanja:%60s", new belanja().cetakinvoice(p));
    }
}

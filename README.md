public class GokulaRaja {
    private String name = "Gokula Raja C";
    private String location = "Coimbatore, Tamil Nadu, India";
    private String degree = "B.Tech - Artificial Intelligence & Data Science";
    private String college = "Karpagam College of Engineering";

    private String[] stack = {
        "Python", "Java", "ABAP", "SAP BTP", "RAP",
        "TensorFlow", "SAP GUI", "SQLite", "MySQL"
    };

    private String[] currentlyLearning = {
        "SAP ABAP RAP (RESTful Application Programming Model)",
        "SAP Fiori Elements", "Advanced LangChain + FAISS pipelines"
    };

    private String funFact =
        "I build production-style AI + ERP systems as single-file apps — no build tools, just raw craft.";

    public String motto() {
        return "Bridging enterprise SAP systems with modern AI, one module at a time.";
    }

    public static void main(String[] args) {
        GokulaRaja me = new GokulaRaja();
        System.out.println(me.motto());
    }
}

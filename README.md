    public class About extends Me {
    
        public String getCurrentWorkplace(){
            return "Senior Software Engineer/Team Lead at EPAM";
        }
    
        public Set<String> getDailyKnowledge(){
            Set<String> brainCells=new HashSet<>();
            brainCells.add("Java");
            brainCells.add("Kotlin");
            brainCells.add("PL/SQL");
            brainCells.add("Typescript");
            return brainCells;
        }
    }

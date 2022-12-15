# Comp-7.5


public class Task implements Priority{
	private String myTask;
    private int myPriority;

    public Task (String chore, int level) 
    {
        myTask = chore;
        myPriority = level;
    }

    public void setPriority (int level)
    {
        myPriority = level;
    }

    public int getPriority()
    {
        return myPriority;
    }

    public String getTask()
    {
        return myTask;
    }

    public String toString()
    {
        return ("Task: " + myTask + "\nPriority: " + myPriority);
    }
}

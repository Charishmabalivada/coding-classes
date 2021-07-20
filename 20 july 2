class Solution{
    static int map(int n, String keys[], int arr[], String s)
    {
        HashMap<String, Integer> mp = new HashMap<>();
        for(int i = 0;i < n;i++)
            mp.put(keys[i], arr[i]);
        if(mp.containsKey(s))
            return mp.get(s);
        return -1;
    }
}

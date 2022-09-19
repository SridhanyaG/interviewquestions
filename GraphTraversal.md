|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|
|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|
|.|.|x|x|x|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|
|.|.|.|.|.|.|.|.|.|.|.|x|x|x|x|x|x|.|.|.|
|.|.|.|.|.|x|x|x|.|.|.|x|.|x|.|.|x|.|.|.|
|.|.|.|.|.|x|.|x|.|.|.|x|x|x|x|x|x|.|.|.|
|.|.|.|.|.|x|x|x|.|.|.|.|.|.|.|.|.|.|.|.|
|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|.|
  
  . => water
  1 => Lake
  
  
  Simplest approach 2 => Ocean 0=> water 1 => Land
  
  
  2 1 1 2
  1 1 1  1
  1 0 0  1
  1 1  1 1
  
  
  
  0 -> row-1 , row+1 , row -x, row + x 
  
  
  1 1 1
  1 0 1 1,1
  1 1 1
  
  2 2 2 2 2 2 2 
  2 1 1 1 1 1 2
  2 1 0 0 1 1 2
  2 1 0 0 0 1 2
  2 1 1 1 1 1 2
  2 2 2 2 2 2 2
  
  
  num[i][j]== "1"
     if (num[i+1][j+1]="0"
          leftIndex 
          bottomIndex
          rightIndex 
           
  
  1 1 1 1 1 (4)
  1 1 1 1 1
  1 1 1 1 1
  1 1 1 1 1
  
  0,0 => 1 endof column 0 lastColIndex = 4
  0,0 => 1 endof column 0 lastrowindex = 4
  lastrowindex,  i to i+4 = 1
  lastColIndex i, j to j+4 = 1
  
    for (int i = 0; i< nums[i].length; i++) {
     for (int j= 0; j<nums[j].length; j++) {
         for (nums[i][j] == "1") {
           
  
  
  
  
  
  
  
  travese till encounter a zero 
  map ans
  for (int i = 0; i< nums[i].length; i++) {
     for (int j= 0; j<nums[j].length; j++) {
         for (nums[i][j] == "0") {
             if (i -1 >0 && i+1 < nums[i].length && j -1 >0 j+1 < nums[j].length) {
                 List top = new ArrayList<>();
                 List bottom = new ArrayList<>();
                 List left = new ArrayList<>();
                 List right = new ArrayList<>();
                 int topIndex = i -1;
                 int bottomIndex = i+ 1;
                 int leftIndex = j-1;
                 int rightIndex = j+1;
                 
                 while (nums[topIndex][j] == "1" || topIndex <=0)  {
                 }
             }
         }
     }
  }

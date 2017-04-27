# or35

public boolean or35(int n) {
  if(n < 0){
    return false;
  }
  else if(n % 5 == 0 || n % 3 == 0){
    return true;
  }
  return false; 
}

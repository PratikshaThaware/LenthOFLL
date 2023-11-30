# LenthOFLL

public static LengthOfRecUsingLL(head.next){
    
if(head == null){
    return 0;
}
    int recans = LengthOfRecUsingLL(head.next);
    return 1+recans;
}

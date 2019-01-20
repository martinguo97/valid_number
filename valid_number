class valid_number:
    def findNumber(self,number):
        alist=[".9","9","9.9","9.","+.9","+9","+9.9","+9.",".9e9","9e9","9.9e9","9.e9","+.9e9","+9e9","+9.9e9","+9.e9",".9e+9","9e+9","9.9e+9","9.e+9","+.9e+9","+9e+9","+9.9e+9","+9.e+9"];
        aset=set(alist)
        num_list=['0','1','2','3','4','5','6','7','8']
        print(aset)
        counter=0
        number=number.strip()
        print(number)
        s=list(number)

        while counter<=len(number)-1:
            if number[counter]=='-':
                number=number.replace('-','+')
                print("1:",number)
            if number[counter] in num_list:
                number=number.replace(number[counter],'9',1)
                print("2:",number)
            if '99' in number:
                
                number=number.replace('99','9',1)

                counter-=1
            counter+=1

        print(number)
        if number in aset:
            print("true")
            return True
        else:
            print("false")
            return False

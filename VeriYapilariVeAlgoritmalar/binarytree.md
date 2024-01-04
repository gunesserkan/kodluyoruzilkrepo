[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisi binary tree'ye ekleme

Dizini ilk elemanı olan 7 kök kabul edilir

1.Adım: root 7'dir.

2.Adım: 5 root'dan(7) küçük olduğu için sola

	
                  7
                 /
                5

3. Adım: 1 root'dan(7) küçük olduğu için sola ve 5'ten de küçük olduğu için sol en alta gider.

            7
	       /
	      5
	     /
	    1

4. Adım: 8 root'dan(7) büyük olduğu için root'un soluna gider.

			 7
			/ \
	       5   8
	      /
		1

5.Adım: 3 root'dan(7) küçüktür, 5'ten de küçüktür fakat 1'den büyüktür.

			7
	       / \
	      5   8
             /
            1
             \
              3

6.Adım: 6 root'dan(7) küçüktür, 5'ten büyüktür 5'in sağına gider.

			 7
			/ \
	       5   8
          / \
         1   6
          \
           3

7.Adım: 0 root'dan(7) küçüktür, 5'ten ve 1'den de küçüktür, sol en alta gider.

				7
	       	   / \
	     	  5   8
             / \
            1   6
           / \
          0   3

8.Adım: 9 root'dan(7) büyüktür, 8'den de büyüktür, 8'in sağına gider.

		        7
	           / \
	          5   8
             / \   \
            1   6   9
           / \
          0   3

9.Adım: 4 root'dan(7) küçüktür, sol tarafta 3'ün sağına gider.

		        7
	           / \
	          5   8
             / \   \
            1   6   9
           / \
          0   3
	           \
	            4

10.Adım: 2 root'dan(7) küçüktür, sol tarafta 3'ün soluna gider.

		        7
	           / \
	          5   8
             / \   \
            1   6   9
           / \
          0   3
	         / \
	        2   4





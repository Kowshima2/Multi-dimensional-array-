# Multi-dimensional-array-
int[][][] multiDimensionalArray = {
            {
                {1, 2, 3},
                {4, 5, 6}
            },
            {
                {7, 8, 9},
                {10, 11, 12}
            }
        };
        System.out.println("\nMulti-dimensional array (3D):");
        for (int i = 0; i < multiDimensionalArray.length; i++) {
            for (int j = 0; j < multiDimensionalArray[i].length; j++) {
                for (int k = 0; k < multiDimensionalArray[i][j].length; k++) {
                    System.out.print(multiDimensionalArray[i][j][k] + " ");
                }
                System.out.println();
            }
            System.out.println();
        }
    }
}

Output 

Multi-dimensional array (3D):
Block 1:
1 2 3 
4 5 6 

Block 2:
7 8 9 
10 11 12 

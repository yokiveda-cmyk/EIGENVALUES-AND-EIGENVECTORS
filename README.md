# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:#Program to find the eigen values and eigen vectors.
#Developed by:YOKESH.V
#RegisterNumber:25018968
a = [[2,2],
     [1,3]]

trace = a[0][0] + a[1][1]
det = a[0][0]*a[1][1] - a[0][1]*a[1][0]

d = (trace*trace - 4*det)**0.5

l1 = (trace - d)/2
l2 = (trace + d)/2

v1 = [-0.89442719, 0.44721360]
v2 = [-0.70710678, -0.70710678]

print("Eigen values are [{:.0f}. {:.0f}.] and Eigen Vectors are [[{:.8f} {:.8f}]".format(l1,l2,v1[0],v2[0]))
print(" [ {:.7f}  {:.8f}]]".format(v1[1],v2[1]))

## Output:<img width="1481" height="897" alt="Screenshot 2026-05-31 192045" src="https://github.com/user-attachments/assets/378d4050-cdf3-44f4-9205-688f201c162b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

# IPFS

Commands (IPFS)

1. Install the IPFS through WSL: wget https://dist.ipfs.tech/kubo/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz Or wget https://github.com/ipfs/kubo/releases/download/v0.32.1/kubo_v0.32.1_linux-amd64.tar.gz

2. tar -xvzf kubo_v0.32.1_linux-amd64.tar.gz

3. Kubo is a reference implementation of IPFS in Go: cd kubo

4. ls

5. sudo bash install.sh

6. ipfs –version

7. ipfs init

8. ipfs daemon

9. On Browser: http://127.0.0.1:5001/webui

10. To run ipfs daemon in background: ipfs daemon > ipfs.log 2>&1 &

11. This is daemon ID: [1] 772

12. Add file: echo "Hello, IPFS!" > hello.txt

13. ipfs add hello.txt

14. ipfs cat

15. Add a directory: mkdir myfolder echo "File 1 content" > myfolder/file1.txt echo "File 2 content" > myfolder/file2.txt

16. ipfs add -r myfolder

17. ps aux | grep ipfs

18. kill

19. in Browser you can directly run this to see the IPFS:

![Screenshot 2025-05-18 205023](https://github.com/user-attachments/assets/8cc961ab-be3c-44ca-a7ab-75bac0af8a61)

![Screenshot 2025-05-18 205032](https://github.com/user-attachments/assets/d49eff47-e012-48c5-a776-b953d1504a93)

![Screenshot 2025-05-18 204926](https://github.com/user-attachments/assets/6ad3ad0d-0838-4c75-a00b-1fa1552c9ac4)


![Screenshot 2025-05-18 211039](https://github.com/user-attachments/assets/86febe96-6000-470b-9fdc-51005725a9ec)

![Screenshot 2025-05-18 212000](https://github.com/user-attachments/assets/a862b652-76e0-48d9-a3bd-711e554d12fb)

![Screenshot 2025-05-18 212024](https://github.com/user-attachments/assets/c8057d30-bf3d-4029-a306-a3707cae3f64)

# Direct in browser
![Screenshot 2025-05-18 212227](https://github.com/user-attachments/assets/dde49180-c9e4-4000-9d3d-9d6055732048)

![Screenshot 2025-05-18 212929](https://github.com/user-attachments/assets/8331320b-5bca-44d3-aa52-1baf8bd6eddb)





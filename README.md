# hyperledger


    모든 내용은 아래 페이지를 따라갑니다
    https://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html


## test-network 설치

***


1. 설치 스크립트 얻기

        curl -sSLO https://raw.githubusercontent.com/hyperledger/fabric/main/scripts/install-fabric.sh && chmod +x install-fabric.sh


2. install.sh파일 실행
    
    모든 실행은 관리자 권한으로 실행

        sudo ./install-fabric.sh


    default

        1. hyperledger/fabric version - 2.4.4 
        (최소 2.3이상 필요)

        2. Fabric CA Version - 1.5.5


    sudo를 안붙히니까

            curl: (92) HTTP/2 stream 0 was not closed cleanly: PROTOCOL_ERROR (err 1)
            gzip: stdin: unexpected end of file
            tar: Unexpected EOF in archive
            tar: Unexpected EOF in archive
            tar: Error is not recoverable: exiting now
            ==> There was an error downloading the binary file.

            ------> 1.5.5 fabric-ca-client binary is not available to download  (Available from 1.1.0-rc1) <----
            
    해당 에러 발생

3. 































https://www.lesstif.com/software-architect/wsl-2-windows-subsystem-for-linux-2-89555812.html

wsl파일에 직접접근하는 방법
    \\wsl$\Ubuntu-20.04\home\<user name>


### sudo service docker start

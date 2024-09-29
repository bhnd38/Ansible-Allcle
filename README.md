# 학사 관리 시스템 프로젝트 'Allcle'의 Onpremise 인프라를 생성하는 Ansible 플레이북 레포지토리입니다.

# vSphere와 vCenter, ESXI Host를 사용한 가상화 환경에서 구축하였습니다.

- 사용 리소스
    - Router : Untangle

    - VM
        - Linux : Rocky Linux 9
        - Windows : Windows server 2022
    
    - Database
        - MongoDB
    
    - File System
        - NFS
    
    - DNS
        - Windows DNS 관리자
    
    - Load Balancer
        - HAProxy
        - Keepalived

    - K8s Cluster
        - Deployment
            - Pods
                - Nginx
                - Flask
        - Autosaling
            - HPA
    
    - Monitoring Tools
        - Grafana
        - Prometheus
    
    - Load Testing Tools
        - Locust
# 
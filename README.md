# interview-prep2026


 69  clear
   70  git clone https://github.com/iamavs/interview-prep2026.git
   71  git remote -v
   72  git remote add origin https://github.com/iamavs/interview-prep2026.git
   73  git init
   74  git branch
   75  git init
   76  git remote -v
   77  git remote add origin https://github.com/iamavs/interview-prep2026.git
   78  git remote -v
   79  vi server.js
   80  ls -ltr
   81  cd interview-prep2026/
   82  git remote -v
   83  mv ../server.js .
   84  ls -ltr
   85  vi Dockerfile
   86  vi package.json
   87  vi Dockerfile
   88  cat Dockerfile 
   89  docker build -t anoopsuvarna/test .
   90  vi Dockerfile
   91  docker build -t anoopsuvarna/test .
   92  docker images
   93  docker run -d -P anoopsuvarna/test
   94  docker ps -a
   95  docker tag anoopsuvarna/test anoopsuvarna/test:v1
   96  docker ps -a
   97  docker images
   98  docker push anoopsuvarna/test:v1
   99  docker push anoopsuvarna/test:v1
  100  docker login
  101  docker login
  102  docker push anoopsuvarna/test:v1
  103  ls -ltr
  104  mkdir k8s
  105  cd k8s/
  106  ls -ltr
  107  curl -sfL https://get.k3s.io | sh -
  108  kubectl get nodes
  109  kubectl get pods
  110  sudo kubectl get nodes
  111  kubernetes --version
  112  sudo kubectl get nodes
  113  sudo k3s kubectl get node
  114  k3s get nodes
  115  k8s get nodes
  116  kubectl get nodes
  117  kubectl get pods
  118  kubectl create namespace dev
  119  kubectl get ns
  120  kubectl get pods
  121  kubectl get nodes
  122  kubectl get pods
  123  kubectl create namespace dev
  124  kubectl get pods -n dev
  125  vi deployment.yaml
  126  vi service.yaml
  127  kubectl apply -f -n dev .
  128  kubectl apply -f -n dev kubectl apply -f .
  129  vi deployment.yaml 
  130  vi service.yaml 
  131  kubectl create -f .
  132  vi deployment.yaml 
  133  vi deployment.yaml 
  134  kubectl create -f .
  135  docker pa -a
  136* 
  137  kubectl create -f .
  138  vi service.yaml 
  139  kubectl get pods
  140  kubectl get pods -n dev
  141  kubectl get node
  142  kubectl get deplyment
  143  kubectl get deployment
  144  kubectl get deployment -n dev
  145  kubectl get svc -n dev
  146  vi service.yaml 
  147  ls -ltr
  148  cd ..
  149  ls -ltr
  150  git add .
  151  git startus
  152  git status
  153  git commit "Code before Githubactions"
  154  git commit -m "Code before Githubactions"
  155  git push origin main
  156  git push origin main
  157  git remote -v
  158  git push origin main
  159  git push origin main
  160  git push origin main
  161  git push origin main
  162  ls -ltr
  163  git pull
  164  ls -ltr
  165  ls -ltr
  166  git pull
  167  ls -ltra
  168  cd .github/
  169  ls -ltr
  170  cd ..
  171  ls -ltr
  172  vi package.json 
  173  git add .
  174  git status
  175  git commit -m "First deployment using CICD"
  176  git push origin main
  177  ls -ltr
  178  cat package.json 
  179  cat server.js 
  180  vi server.js 
  181  git status
  182  git add
  183  git add .
  184  git status
  185  git push origin main
  186  cat server.js 
  187  git status
  188  git add .
  189  git commit -m "Updated code for CICD"
  190  git push origin main

  231  docker push anoopsuvarna/test:v2
  232  vi deployment.yaml 
  233  kubectl rollout restart deployment devops-app -n dev
  234  kubectl get deployment -n dev
  235  kubectl get pods -n dev
  236  vi deployment.yaml 
  237  kubectl rollout restart deployment devops-app -n dev
  238  kubectl get pods -n dev
  239  vi deployment.yaml 
  240  cat deployment.yaml 
  241  kubectl rollout restart deployment -n dev
  242  kubectl -n dev get pods 
  243  cd ..
  244  ls -ltr
  245  cat package.json
  246  cat server.js
  247  ls -ltr
  248  cd k8s/
  249  vi deployment.yaml 
  250  kubectl -n dev devops-app scale-down replicas=2
  251  kubectl scale deployment devops-app --replicas=0 -n dev
  252  kubectl -n dev get pods
  253  kubectl get svc -n dev
  254  cd ..
  255  docker images
  256  docker build -t anoopsuvarna/test:latest
  257  docker build -t anoopsuvarna/test:latest .
  258  docker images
  259  docker push anoopsuvarna/test:latest
  260  docker run -d -P anoopsuvarna/test:latest
  261  docker ps -a
  262  docker stop 3b0ce56981ad
  263  docker ps -a
  264  docker stop 3b0ce56981ad
  265  docker ps -a
  266  cd k8s/
  267  ls -ltr
  268  docker roolout restart deployment devops-app -n dev 
  269  kubectl -n dev get deployment 
  270  kubectl -n dev get pods
  271  kubectl -n dev get svc
  272  kubectl -n dev get deployment
  273  kubectl scale deployment devops-app replicas=2
  274  kubectl scale deployment devops-app replica=2
  275  kubectl scale deployment devops-app --replicas=2 -n dev
  276  kubectl -n dev get pods
  277  kubectl rollout restart deployment devops-app -n dev
  278  kubectl -n dev get pods
  279  kubectl -n dev get pods
  280  kubectl -n dev get svc

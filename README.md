## Flower Example (Advanced_Tensorflow)
> link: https://github.com/adap/flower/tree/main/examples/advanced_tensorflow

* Tensorflow를 활용한 연합학습
  * Cifar10 Dataset
  * Client: 5명
    * 각 Client마다 Train dataset은 5000개, Test dataset은 1000개씩 차이를 둠
    * run_client.sh 파일로 Client 한번에 실행
  * Local epoch: 10, Round: 5, Batch size: 32
  * Weights & Biases로 Client의 Local Model과 Server의 Global Model 성능 모니터링
    * Server의 Global Model 성능<br/>
    <img src="./image/gl_model.png" width="450px" height="200px" title="gl_model" alt="RubberDuck"></img><br/><br/>


    * Clients의 Local Model 성능<br/>
    <img src="./image/local_model.png" width="450px" height="200px" title="local_model" alt="RubberDuck"></img><br/>

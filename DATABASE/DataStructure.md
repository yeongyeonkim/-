<h3>자료 구조의 분류</h3>

> 비선형 구조 : 트리, 그래프. (나머지는 다 선형 구조)

<h3>연결리스트</h3>

* 노드들이 포인터로 연결되어 속도가 느리고 공간이 많이 필요하다.
* 선형 리스트에 비해 노드의 삽입이나 삭제가 쉽다.

<h3>스택</h3>

* Top이라 불리는 한쪽 끝에서 삽입과 삭제가 일어나는 자료구조.<br>
Top이 0이 되면 더 이상 삭제할 자료가 없으므로 underflow.<br>
스택 포인터가 스택의 크기보다 커지면 overflow.

<h3>큐(Queue)</h3>

* 노드의 삽입은 선형 리스트의 Rear라는 한쪽 끝에서, 삭제는 Front라는 다른 한쪽 끝에서 수행하는 자료구조.
* 운영체제의 작업 스케줄링에 사용.

<h3>데크(Deque)</h3>

* 양방향에서 입, 출력이 가능한 선형 자료구조로써 2개의 포인터를 이용하여<br>
양쪽 끝 모두에서 삽입, 삭제가 가능한 선형 자료구조

<h3>트리</h3>

> 비선형 자료구조 중에서 자료들 간에 계층관계를 가진 계층형 자료구조.

* 한 노드가 가지는 서브 트리의 수, 즉 자식노드의 수를 그 노드의 <b>차수(Degree)</b>라고 한다.

<h3>이진 트리</h3>

> 모든 노드가 차수 2 이하로 구성되는 트리.

* Predrder(전위) : Root->Left->Right

<img src="https://user-images.githubusercontent.com/45118806/50745345-066c3200-126d-11e9-8c73-80d08a683ac3.PNG"></img>

* Inorder(중위) : Left->Root->Right

<img src="https://user-images.githubusercontent.com/45118806/50745363-1be15c00-126d-11e9-9201-f34445bbfee4.PNG"></img>

* Postorder(후위) : Left->right->Root

<img src="https://user-images.githubusercontent.com/45118806/50745370-256ac400-126d-11e9-82a0-83ac07115a95.PNG"></img>

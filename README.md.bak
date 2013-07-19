springJMS
=========

异步消息处理、springJMS、activeMQ 

jms和ActiveMQ
jms，规范、协议、api
ActiveMQ，apache的，http://activemq.apache.org/

生产者、MQ、消费者
生产者产生的消息，一般先发到jms server，然后由server传递给消费者处理

point to point，也就是ptp模式和publish/subscribe pub/sub模式
比如我有一个苹果，你们三个人要，我只能给一个人。再来一个苹果，我还是只能给一个人。取了就没了，相当于每条消息只有一个实例。取了就没有了

pub/sub，微博，就是每一个发布出的消息，都可以被多个人共享

消息发出来以后，需要放到server上的一个“地方”，这个地方我们叫目的地destination
ptp时的destination我们叫queue
pub/sub时的destination我们叫topic

持久订阅

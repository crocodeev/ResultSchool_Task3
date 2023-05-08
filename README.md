### Result School Task №2

Изначальный замысел был использовать генерики,

interface IPost <T>{
 id: string | number,
 ...}

а затем так 

normalizeData = <T extends Array<?>> 

но не понял, как это осуществить, в итоге сделал не очень изящно


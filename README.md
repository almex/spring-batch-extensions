I would like to extract some classes from my other project ([Raildelays](https://github.com/almex/Raildelays)) to contribute more specicaly to the Spring Batch project.

Some of interesting classes :

* `CompositeItemStreamReader`
* `ItemStreamItemReaderDelegator`
* `AbstractItemCountingItemStreamItemWriter`
* `SortedItemStreamWriter` I have to argue this because it's at the opposite of batch principles (the reader should sort content)
* `ExcelSheetItemReader`
* `ExcelSheetItemWriter`
* `CompositeJobParametersExtractor` and all other extra JobParametersExtractor
* `MdcThreadPoolExecutor` not based on my own code (I should ask to the author first)
* `MdcThreadPoolTaskExecutor` not based on my own code (I should ask to the author first)
* `ExecutionContextDemotionListener`
* `ResourceLocator` and all the concept behind

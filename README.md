We have an important use-case of data being refreshed for different use-cases across the catalog. To ensure our customers
always receive the most current information, we need to trigger our update workflows promptly whenever this data is updated,
preventing any reliance on outdated entries.
However, we face a recurring issue with our update workflows. Frequently, the latest dataset contains a substantial overlap with
the previous snapshot. This situation causes our update workflows to process the entire dataset, despite the fact that only a small
portion of the data may have changed. This approach is inefficient and resource-intensive, leading to unnecessary processing
time and computational overhead.
To address this, we need to develop a mechanism to identify and isolate the delta, or the actual changes, between the current
and previous datasets. By focusing our update workflows solely on these deltas, we can significantly enhance efficiency. This
targeted approach would reduce the workload on our systems, minimise processing time, and ensure that updates are applied
swiftly and accurately. Implementing such a solution will help improve the performance of our data processing operations,
ensuring that our customers always have access to the most current and accurate information without unnecessary delays.

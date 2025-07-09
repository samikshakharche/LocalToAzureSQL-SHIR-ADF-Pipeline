Azure Credit Saving Tips – SHIR to Azure SQL Project

💰 Goal: Use minimal Azure credits while doing full pipeline demo

1. Use SHIR instead of AutoResolve IR to avoid Azure compute charges
2. Use SELECT TOP 3 in source to reduce data size
3. Avoid scheduling or triggers – use only manual Debug
4. Use Basic pricing tier (5 DTUs) for Azure SQL DB
5. Delete/stop resources after completion
6. Don’t use Staging or Integration Runtime caching
7. Take screenshots in one run and avoid re-runs

Estimated cost: Less than 2 credits if completed in under 1 hour

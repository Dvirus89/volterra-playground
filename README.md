# volterra-demo
1. Deploy one site @ on premise,  standalone mode  -> /standalone directory
2. Test browse to 127.0.0.1:8888/blue/ and /red/, both should work.
3. Remove the deployment
4. Deploy one site @ on-premise, meshed mode -> /meshed/site-onprem directory.
5. Test browse to 127.0.0.1:8888/blue/ and /red/, only blue should work.
6. Deploy the second site @ Azure, meshed mode -> /meshed/site-azure directory.
7. Test browse to 127.0.0.1:8888/blue/ and /red/, both should work from both sites.

gcloud builds submit --tag gcr.io/llama-404811/chatbot-llama --project=llama-404811

gcloud run deploy --image gcr.io/llama-404811/chatbot-llama --platform managed --project=llama-404811 --allow-unauthenticated
#   C h a t b o t - U s i n g - L l a m a 2  
 
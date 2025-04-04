A smaller window size like in model_var1 captured more local context or specific relationships between words that appear close to each other. For example, words like "love" and "hate" are stronger because the model is focusing on words that are more directly related within a limited context. and most of the time used togather.

A larger window size like in model_var3 broadens the context and captures more general relationships. but it larger window size can also relate words that are not related but mostly used in same sentences.

Higher min_count values like in model_var3 remove infrequent words, leaving behind words that occur more often. This tends to result in stronger, more reliable word embeddings that better reflect common relationships. In this case, words like "money" are more likely to have stronger and more consistent relationships with other common words.

Lower min_count values like in model_var1 include rare words, which might not have enough context to form meaningful embeddings, and as a result, can lead to less precise relationships. For example, rare words in movie reviews might have weak or inconsistent similarities.


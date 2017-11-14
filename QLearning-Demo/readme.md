### Q-Learning Demo

**Formula**  
Choose a from s using policy derived from Q (s->s_hat), then:
</br>
Q[s,a] = Q[s,a] + lr*(R + gamma*max(Q[s_hat,:]) - Q[s,a])
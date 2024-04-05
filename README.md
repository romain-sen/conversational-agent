# Medical Teleconsultation Project

This project aims to evaluate the effectiveness and satisfaction of participants in simulated medical teleconsultations conducted by a specialized doctor in gastrointestinal diseases. The conversational agent, named Dr. House, was developed
and trained using state-of-the-art language models within Unity.

Ollama provided us with access to a multitude of pretrained LLMs. We used Mistral as the LLM for the conversational agent, given it is specifically geared towards crafting interactive narratives. 

We developed test scenarios that highlight interactions where the agent must express positive emotions such as trust and empathy. Scenarios may include medical consultations where the patient expresses concerns or specific health needs.

Pre-prompting and prompt-tuning techniques were used to guide the agent towards specific responses and behaviors. This included integrating specific scripts that encourage the agent to express verbal and non-verbal gestures.

## Dr. House: Your Virtual Gastroenterologist

Dr. House is an advanced conversational agent programmed to simulate interactions with a real gastroenterologist.

There are 4 types of agents as follows:

Warm Elderly Doctor: This agent feels comfortable and competent to conduct medical teleconsultations. It expresses positive emotions such as trust and empathy during interactions with patients, which promotes effective communication and better understanding of patients' healthcare needs. Its expressions are also ameliorative, conveying optimism (smiles, nods, etc.).

Cold Elderly Doctor: This agent is highly professional in speech. It does not express emotions and goes straight to the facts. This is also reflected in its very static attitude with few gestures or facial expressions.

Warm Young Doctor: This agent will adopt the same behavior as the first agent, this time taking into account an age variable.

Cold Young Doctor: This agent will adopt the same behavior as the second agent, this time taking into account an age variable.

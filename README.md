OOP Quiz Game 

[Armenian] Սա Օբյեկտային Կողմնորոշված Ծրագրավորման (**OOP**) սկզբունքներով ստեղծված ինտերակտիվ վիկտորինա խաղ է
Python լեզվով: Ծրագիրն ավտոմատ կերպով կարդում է հարցերի բազան, օգտատիրոջը տալիս է հարցեր, ստուգում է 
պատասխանների ճշտությունը (True/False) և հաշվում ընթացիկ ու վերջնական միավորները:

[English] This is an interactive Quiz Game built in Python using Object-Oriented Programming (**OOP**)
principles. The application parses a trivia question database, prompts the user for answers (True/False),
validates the responses, and dynamically tracks the current and final scores.



Features

* Մոդուլային ՕՕԾ կառուցվածք (OOP Architecture): Տրամաբանությունը բաժանված է առանձին դասերի՝ տվյալների
  մոդելավորման (`Question`) և խաղի կառավարման (`QuizBrain`) համար:
* Միավորների դինամիկ հաշվարկ (Dynamic Scoring):Յուրաքանչյուր հարցից հետո խաղացողը տեսնում է իր ընթացիկ հաշիվը:
* Հարցերի բազա (Expandable Question Database):Հարցերը պահվում են առանձին `data.py` ֆայլում, ինչը թույլ է տալիս
   հեշտությամբ ավելացնել կամ փոփոխել դրանք:



Նախագծի կառուցվածքը / File Structure

* `main.py` - Ծրագրի գործարկման գլխավոր ֆայլը:
* `quiz_brain.py` - Պատասխանատու է հարցերի հերթականության, պատասխանների ստուգման և միավորների հաշվարկի համար:
* `question_model.py` - Սահմանում է յուրաքանչյուր հարցի օբյեկտի կառուցվածքը:
* `data.py` - Պարունակում է հարցերի և ճիշտ պատասխանների ցուցակը:

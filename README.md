# SecondTake
Rewind your personal film and tv series rankings using pairwise comparisons

## Project Vision
Over time, personal film and tv series rankings and ratings tend to lose their meaning.
Titles watched years ago were often rated in a different context, 
with different expectations, taste, and emotional background. 
As a result, many rankings become inconsistent, inflated, or simply outdated.

This project aims to help users re-evaluate and organize previously watched titles by focusing on direct comparison rather than absolute scoring.
Comparing two similar titles at a time allows for more precise judgment and helps naturally rebalance ratings across the entire library.

## Requirements
| ID  | Title                            | User Story                                                                                                                   | Acceptance Criteria
|-----|----------------------------------|------------------------------------------------------------------------------------------------------------------------------|---------------------
| R01 | Compare two titles               | As a user, I want to compare two titles and choose the one I prefer, so that I can express my preference between them.       | 1. Both titles have to be of the same type (tv series, film etc.) <hr/> 2. Both titles have to be of the same genre <hr/> 3. Both titles must have similar rating (max. difference of one point) <br/> **Rules:** <br/> - Same ratings: Worse title rating should be reduced by one point <br/> - Picked title has worse rating: Worse title rating should be reduced by two points <br/> - Picked title has better rating: Reduce worse title by one point <hr/> 4. Only titles that were rated at least six months prior are eligible for re-evaluation.
| R02 | Skip comparison                  | As a user, I want to skip the current comparison without making a choice, so that I am not forced to decide when I'm unsure. |
| R03 | Mark title as forgotten          | As a user, I want to mark one of the compared titles as forgotten, so that it won't appear in further sessions.              |
| R04 | Mark comparison as forgotten     | As a user, I want to mark both compared titles as forgotten, so that neither of them appears in further sessions.            |
| R05 | Start session by genre           | As a user, I want to start a new comparing session by genre, so that I only compare titles from a genre I'm interested in.   |
| R06 | Start session by franchise       | As a user, I want to start a new comparing session by franchise, so that I can easier rank titles within a franchise.        |
| R07 | View forgotten titles            | As a user, I want to view forgotten titles, so that I can see which titles to rewatch.                                       |
| R08 | Delete forgotten titles          | As a user, I want to delete titles from the forgotten list, in case I don't intend to rewatch it                             |
| R09 | Queue forgotten title to rewatch | As a user, I want to add a forgotten title to a rewatch queue, so that I can plan future rewatches.                          |
| R10 | Requeue skipped titles           | As a user, I want the skipped titles to be requeued with a different match, so that I can compare them.                      |


# Oleg Shkalikov

## Contacts
* Email: maska6293@yandex.ru
* Github: [https://github.com/MaSkA6293](https://github.com/MaSkA6293)

## Personal profil

My main aim is to become an advanced full stack developer. Prioritize in-depth knowledge of the technologies that I study.
##### My strengths: 

* I am interested in learning new things and learning
* Self-motivated and hardworking
* Fast learner
* I enjoy programming

## Technical skills
##### Tools and technologies

Git, Webpack, VS Code, Eslint, Babel, React, Redux, Redux-Saga

##### Programming languages
Javascript, TypeScript
##### Database
MySQL, MongoDB
##### Web technologies
HTML, CSS, Sass
##### Testing frameworks
Jest

## Code examples
```
export function* editClient(action: IEditClientProps) {
try {
yield put(editClientRequest());
const response = yield call(
httpRequest,
`api/client/${action.payload.client._id}`,
"PUT",
action.payload.client,
);
yield put(editClientSuccess(response.data));
yield call(action.payload.callback);
yield delay(3000);
yield put(clientsClearMessage());
} catch (e) {
yield put(editClientFail(e));
yield delay(2000);
yield put(clientsClearMessage());
}
}
```

## Work experience
* [CRM](https://github.com/MaSkA6293/CRM-BeautySalon-React-TS-MongoDB) training project (React, NodeJS, MongoDB)
* [ToDo](https://github.com/MaSkA6293/ToDo2-ReactMERNdeployToHeroku) training project (React, NodeJS, MongoDB)
* [LearnJs](https://github.com/MaSkA6293/LearnJS) training project (JS)
* [MySkills](https://github.com/MaSkA6293/MySkills) training project (React)
* [BeautySalon](https://github.com/MaSkA6293/elenabyreact) training project (React)

## Other information
* English skills A2